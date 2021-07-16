<template>
  <div id="app">
    <Componente1 />
     <Componente1 />
      <Componente1 />

      
  </div>
</template>

<script>
import Componente1 from './components/Componente1'

export default {
  name: 'App',
  components: {
    Componente1
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
