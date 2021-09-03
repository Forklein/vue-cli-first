<template>
  <div id="app">
    <Title></Title>
    <Hero></Hero>
  </div>
</template>

<script>
import Hero from "@/components/Hero.vue";
import Title from "@/components/Title.vue";

export default {
  name: "App",
  components: {
    Title,
    Hero,
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: burlywood;
}

#app {
  text-align: center;
}
</style>
