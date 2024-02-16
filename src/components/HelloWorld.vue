<template>
 <div>
  <h1>Hello World</h1>
 </div>
 <div style="font-size: 30px; font-family: 'Poppins', sans-serif;">
 <p>{{nombre}}</p>
 <p>{{ grupo }}</p>
 <p>{{ matricula }}</p>
 </div>
</template>

<script>
export default {
  data(){
    return{
      nombre: 'Luis Gerardo Alvarado Moreno',
      grupo: '5A',
      matricula: '20963' 
    }
  }
}
</script>