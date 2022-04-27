<template>
  <div id="app">
    <HeaderComponent />
    <MainComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import MainComponent from "./components/MainComponent.vue";

export default {
  name: "App",
  components: {
    HeaderComponent,
    MainComponent,
  },
};
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
@import "~@fontsource/montserrat/index.css";
@import "~@fontsource/montserrat/700.css";
.color-green {
  color: #1fad96;
}
.color-grey {
  color: #9ea4a5;
}
.bg-lightgrey {
  background-color: #f6f3f5;
}
.ff-btn {
  color: white;
  background-color: #1fad96;
  padding: 10px 20px;
}
</style>
