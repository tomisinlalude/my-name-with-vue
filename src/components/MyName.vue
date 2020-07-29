<template>
  <div id="app" class="mt-5">
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
}
</style>