<template>
  <div id="app">
    <HeaderComponent />
    <MainComponent />
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import MainComponent from "./components/MainComponent.vue";
import FooterComponent from "@/components/FooterComponent.vue";

export default {
  name: "App",
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent,
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
.color-blue {
  color: #3f3a64;
}
.color-grey {
  color: #9ea4a5;
}
.color-lightgrey {
  color: #f6f3f5;
}
.bg-lightgrey {
  background-color: #f6f3f5;
}
.ff-btn {
  color: white;
  background-color: #1fad96;
  padding: 10px 20px;
}
.ff-btn:hover {
  background-color: #3f3a64;
  color: white;
}
</style>
