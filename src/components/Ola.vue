<template>
  <div class="ola">
    <h1>{{ message }}</h1>
    </div>
</template>

<script>
export default {
  name: 'Ola',
  props: {
    message: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
  background-color: #f98000;
  text-align:center;
  font-size: 50px;

}
</style>
