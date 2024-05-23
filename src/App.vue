<script>
import HelloWorld from './components/HelloWorld.vue';
export default {
  components: {
    HelloWorld,
  },

  data() {
    return {
      versione: 0.1,
      utente: 'Spadoni Giacomo',
    };
  },
};
</script>

<template>
  <h1>Stai utilizzando la versione {{ versione }}</h1>
  <h2>Buongiorno {{ utente }}</h2>
  <HelloWorld />
</template>

<style></style>
