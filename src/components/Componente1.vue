<template>
  <div>
     <input v-model="nome"/>
     <p> o valor inserido é <b>{{nome}}</b> </p>
     <div>
        <button @click='limpar'> limpar </button>
     </div>
  </div>
</template>

<script>
  export default {
    name: 'Componente1',

    data:function(){
      return {
        nome:""
      }
    },

    methods:{
      limpar:function(){
        this.nome=''
      }
    }
  }

</script>

<style>
  *{
    color:red;
  }


</style>