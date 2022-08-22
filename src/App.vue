<template>
  <div>
    <StarbucksHeader />
    <StarbucksMain />
    <StarbucksFooter />
  </div>
</template>

<script>
import StarbucksHeader from "./components/StarbucksHeader.vue";
import StarbucksMain from "./components/StarbucksMain.vue";
import StarbucksFooter from "./components/StarbucksFooter.vue";
export default {
  name: "App",
  components: { StarbucksMain, StarbucksFooter, StarbucksHeader },
};
</script>

<style></style>
