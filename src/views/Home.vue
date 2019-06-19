<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Component msg="Un composant avec Vue"/>
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
