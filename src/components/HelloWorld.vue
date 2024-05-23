<script>
export default {
  data() {
    return {
      msg: 'helloworld',
    };
  },
};
</script>

<template>
  <h2>sono l'h2 dei components e mi chiamo {{ msg }}</h2>
  <div class="ciao"></div>
</template>

<style scoped>
h2 {
  background-color: rgb(53, 255, 42);
}
</style>
