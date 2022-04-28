<template>
  <footer class="bg-lightgrey py-5">
    <div class="container">
      <div class="row">
        <div class="col-12 col-md-6">
          <h6>Address</h6>
          <p>382 NE 191ST St # 87394 Miami, FL 33179-5574</p>
          <p>+1(305) 547-4434 (9am - 5pm, Monday - Friday)</p>
          <p>support@maxcoach.com</p>
          <div class="d-flex col-6 justify-content-between py-3">
            <i class="fa-brands fa-facebook-square"></i>
            <i class="fa-brands fa-twitter"></i>
            <i class="fa-brands fa-instagram"></i>
            <i class="fa-brands fa-linkedin"></i>
          </div>
        </div>
        <div class="col-12 col-md-6 text-middle">
          <div
            class="d-inline-block px-4 align-top"
            v-for="(item, index) in footerItem"
            :key="index"
          >
            <h6>{{ item.title }}</h6>
            <ul>
              <li v-for="(text, i) in item.text" :key="i">
                <a href="#"> {{ text }}</a>
              </li>
            </ul>
          </div>
        </div>
        <div class="col-12 text-center pt-5">
          <p>
            <i class="fa-solid fa-copyright"></i> MaxCoach. All Rights Reserved
          </p>
        </div>
        <div class="d-flex justify-content-end">
          <button class="btn ff-btn">
            <a href="#"><i class="fa-solid fa-arrow-up"></i></a>
          </button>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
import footerItem from "@/assets/data/footerItem.json";
export default {
  name: "FooterComponent",
  data() {
    return {
      footerItem,
    };
  },
};
</script>

<style lang="scss" scoped>
ul {
  list-style-type: none;
  padding-left: 0;
  li {
    margin-top: 10px;
  }
}
p,
li,
i,
a {
  font-size: 0.8rem;
  color: #9ea4a5;
  text-decoration: none;
}
i {
  font-size: 1.5rem;
}
.text-center i {
  font-size: 0.8rem;
}
button {
  width: 75px;
  height: 75px;
  border-radius: 50%;
  text-align: center;
  button i {
    color: white;
  }
}
</style>