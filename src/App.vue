<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <h1>Primeiro Formulario</h1>
    <Form />
    <h1>Segundo Formulario</h1>
    <Form />
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Ola message="OI Vivi, tudo certo?" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Ola from './components/Ola.vue'
import Form from './components/Form.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Ola,
    Form
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
