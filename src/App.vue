<template>
  <div class="container">
    <app-header />
    <app-main />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
export default {
  name: "app",
  components: { AppHeader, AppMain },
};
</script>

<style>
</style>
