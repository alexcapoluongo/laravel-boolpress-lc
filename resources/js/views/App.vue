<template>
  <div>
    <div class="container text-center mt-4">
      <h1>Questa è la pagina guest di boolpress</h1>
      <WorkInProgress />
    </div>
  </div>
</template>

<script>
import WorkInProgress from "../components/WorkInProgress.vue";

export default {
  name: "App",
  components: {
    WorkInProgress,
  },
};
</script>

<style>
</style>