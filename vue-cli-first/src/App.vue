<template>
  <div id="app">
    <Title/>
    <jumbo/>
  </div>
</template>

<script>
  import Title from './components/Title.vue';
  import jumbo from './components/jumbo.vue';

  export default {
    name: 'App',
    components: {
      Title,
      jumbo
    }
  }
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
