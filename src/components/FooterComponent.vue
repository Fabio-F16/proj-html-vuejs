<template>
  <footer class="bg-lightgrey py-5">
    <div class="container">
      <div class="row">
        <div class="col-12 col-md-6">
          <h6>Address</h6>
          <p>382 NE 191ST St # 87394 Miami, FL 33179-5574</p>
          <p>+1(305) 547-4434 (9am - 5pm, Monday - Friday)</p>
          <p>support@maxcoach.com</p>
          <div>
            <i class="fa-brands fa-facebook-square"></i>
            <i class="fa-brands fa-twitter"></i>
            <i class="fa-brands fa-instagram"></i>
            <i class="fa-brands fa-linkedin"></i>
          </div>
        </div>
        <div class="col-12 col-md-6">
          <div
            class="d-inline-block px-4"
            v-for="(item, index) in footerItem"
            :key="index"
          >
            <h6>{{ item.title }}</h6>
            <ul>
              <li v-for="(text, i) in item.text" :key="i">{{ text }}</li>
            </ul>
          </div>
          <!-- </div> -->
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
import footerItem from "@/assets/data/footerItem.json";
export default {
  name: "FooterComponent",
  props: {
    // linkFooter: Array,
  },
  data() {
    return {
      footerItem,
    };
  },
};
</script>

<style lang="scss" scoped>
</style>