<template>
  <main>
    <JumbotronComponent />
    <CoursesComponent />
    <SmartTutoringComponent />
    <ReviewComponent />
    <StatisticsComponent />
    <BlogsComponent />
    <NewslettersComponent />
  </main>
</template>

<script>
import JumbotronComponent from "@/components/JumbotronComponent.vue";
import CoursesComponent from "@/components/CoursesComponent.vue";
import SmartTutoringComponent from "@/components/SmartTutoringComponent.vue";
import ReviewComponent from "@/components/ReviewComponent.vue";
import StatisticsComponent from "@/components/StatisticsComponent.vue";
import BlogsComponent from "@/components/BlogsComponent.vue";
import NewslettersComponent from "@/components/NewslettersComponent.vue";
export default {
  name: "MainComponent",
  components: {
    JumbotronComponent,
    CoursesComponent,
    SmartTutoringComponent,
    ReviewComponent,
    StatisticsComponent,
    BlogsComponent,
    NewslettersComponent,
  },
};
</script>

<style lang="scss" scoped>
// .col-12 {
//   border: 1px solid black;
// }
</style>