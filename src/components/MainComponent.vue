<template>
  <main>
    <JumbotronComponent />
  </main>
</template>

<script>
import JumbotronComponent from "@/components/JumbotronComponent.vue";

export default {
  name: "MainComponent",
  components: {
    JumbotronComponent,
  },
};
</script>

<style lang="scss" scoped>
// .col-12 {
//   border: 1px solid black;
// }
</style>