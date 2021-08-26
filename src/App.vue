<template>
  <div class="container">
    <Home />
  </div>
</template>

<script>
import Home from "@/components/Home.vue";

export default {
  name: "App",
  components: { Home },
};
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: column;

  align-items: center;
}
</style>
