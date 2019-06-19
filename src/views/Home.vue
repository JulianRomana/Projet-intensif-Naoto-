<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Component msg="Ceci est un composante de base avec Vue"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Component from "../components/Component.vue";

export default {
  name: "home",
  components: {
    Component
  }
};
</script>
