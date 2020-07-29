<template>
  <div id="app">
    <h1 class="text-center align-middle">{{ name }}</h1>
  </div>
</template>

<script>
export default {
  name: "MyName",
  props: {
    name: String,
  },
};
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  color: #2c3e50;
  position: relative;
  top: 45vh;
}
</style>