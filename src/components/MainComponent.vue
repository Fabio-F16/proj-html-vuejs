<template>
  <main>
    <JumbotronComponent />
    <CoursesComponent />
  </main>
</template>

<script>
import JumbotronComponent from "@/components/JumbotronComponent.vue";
import CoursesComponent from "@/components/CoursesComponent.vue";

export default {
  name: "MainComponent",
  components: {
    JumbotronComponent,
    CoursesComponent,
  },
};
</script>

<style lang="scss" scoped>
// .col-12 {
//   border: 1px solid black;
// }
</style>