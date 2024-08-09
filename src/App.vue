<template>
  <div id="app">
    <NavbarComponent msg="Welcome to Your Vue.js App"/>
    <JumbotronComponent/>
  </div>
</template>

<script>
import NavbarComponent from './components/NavbarComponent.vue'
import JumbotronComponent from './components/JumbotronComponent.vue';

export default {
  name: 'App',
  components: {
    NavbarComponent,
    JumbotronComponent
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
  
}
</style>
