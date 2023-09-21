<script>
import Title from "./components/AppTitle.vue"
import Jumbotron from "./components/AppHero.vue"

  export default {
    data() {
      return {
        message: "Hello Vite!",
      }
    },
    components: {
      Title,
      Jumbotron,
    },
  }
</script>

<template>
  <Title></Title>
  <Jumbotron></Jumbotron>
  <h1>{{ message }}</h1>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
