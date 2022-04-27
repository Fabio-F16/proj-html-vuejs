<template>
  <div class="container py-5 flex-column">
    <div class="row justify-content-center">
      <div class="col-3">
        <h1 class="color-green align-middle">O</h1>
      </div>
      <div class="col-6 text-center">
        <h4>Subscribe <span class="color-green">NewsLetters</span></h4>
        <p class="color-grey">
          Enter your email address to register to our newsletter subscription
          delivered on a regular basis!
        </p>
        <div class="row justify-content-center">
          <input
            class="col-9 bg-lightgrey"
            type="text"
            placeholder="Enter your email"
          />
          <button class="col-3 btn ff-btn">Subscribe</button>
        </div>
      </div>
      <div class="col-3">
        <img src="../assets/img/maxcoach-shape-09.png" alt="shape-09" />
        <img src="../assets/img/maxcoach-shape-02.png" alt="shape-02" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NewslettersComponent",
};
</script>

<style lang="scss" scoped>
input {
  border: none;
}
h1 {
  font-size: 3rem;
  opacity: 0.4;
  position: relative;
  top: 90px;
}
img:first-child {
  width: 60%;
}
img:last-child {
  position: relative;
  bottom: 100px;
  bottom: 90px;
}
</style>