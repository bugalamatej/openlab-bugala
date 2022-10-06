<template>
  <div>
    <HelloWorld />
    <why></why>
    <vizia></vizia>
  </div>
</template>

<script>
import HelloWorld from "./components/navbar.vue";
import why from "./components/why.vue";
import vizia from "./components/vizia.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    why,
    vizia,
  },
};
</script>

<style>
#app {
  font-family: "SF Pro Display", sans-serif;
}
</style>
