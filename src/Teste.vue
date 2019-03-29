<template>
    <div id="app">
        <img src="http://vuejs.org/images/logo.png">
        <h1>{{ msg }}</h1>
        <p>{{teste}}</p>
    </div>
</template>

<script>
  import Vue from 'vue';
export default Vue.component('teste',{
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      teste: 'Teste'
    }
  }
});
</script>

<style scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
