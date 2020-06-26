<template>
  <div class="Form">
    <h1>{{titulo}}</h1>
    <h2>{{nome}}</h2>
    <form>
      <input type="text" v-model="nome" placeholder="Digite o seu nome">
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      titulo: "Cadastro",
      nome: ""
    }
  },
  name: 'Form',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
