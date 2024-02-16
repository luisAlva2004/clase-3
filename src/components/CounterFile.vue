<template>
    <h1>{{ counter }}</h1>
    <button @click="incremento()">+</button>
    <button @click="reset()">Reset</button>
    <button @click="decremento()">-</button>
</template>

<script>
import {ref} from 'vue';

export default{
    setup(){
        const counter = ref(0);
        return {counter};
    },

    methods: {
        incremento(){
            this.counter++;
        },

        reset(){
            this.counter = 0;
        },

        decremento(){
            this.counter--;
        }
    }
}
</script>