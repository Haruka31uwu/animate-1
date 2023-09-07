<template>
  <div id="app">
    <main-component class="main"/>
  </div>
</template>

<script>
import MainComponent from './components/MainComponent.vue';
export default {
  name: 'App',
  components: {
    MainComponent
  }
}
</script>

<style>
.main{
  width: 100vw;
  height: 100vh;
  background-color: #f5f5f5;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
