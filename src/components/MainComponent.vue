<template>
  <main>
    <JumbotronComponent />
    <CoursesComponent />
    <SmartTutoringComponent />
    <ReviewComponent />
  </main>
</template>

<script>
import JumbotronComponent from "@/components/JumbotronComponent.vue";
import CoursesComponent from "@/components/CoursesComponent.vue";
import SmartTutoringComponent from "@/components/SmartTutoringComponent.vue";
import ReviewComponent from "@/components/ReviewComponent.vue";
export default {
  name: "MainComponent",
  components: {
    JumbotronComponent,
    CoursesComponent,
    SmartTutoringComponent,
    ReviewComponent,
  },
};
</script>

<style lang="scss" scoped>
// .col-12 {
//   border: 1px solid black;
// }
</style>