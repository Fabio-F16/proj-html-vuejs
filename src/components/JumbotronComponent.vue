<template>
  <div>
    <div class="jumbotron">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-12 col-md-6">
            <h1>Distant learning for further expansion</h1>
            <p>
              Learning is a life-long journey that in fact we nwever find the
              terminate stop. Stop searching, enjoy the process
            </p>
            <button class="btn ff-btn">
              <i class="fa-solid fa-download"></i> Download free guide
            </button>
            <p>
              Have questions?
              <a href="#"
                >Get Free Sample <i class="fa-solid fa-arrow-right-long"></i
              ></a>
            </p>
          </div>
          <div class="col-12 col-md-6">
            <img
              class="rounded-circle w-100"
              src="../assets/img/about-me-profile.jpg"
              alt=""
            />
          </div>
        </div>

        <div class="row justify-content-between">
          <img
            class="logo col-2"
            src="../assets/img/client-logo-01.png"
            alt="Logo01"
          />
          <img
            class="logo col-2"
            src="../assets/img/client-logo-02.png"
            alt="Logo02"
          />
          <img
            class="logo col-2"
            src="../assets/img/client-logo-03.png"
            alt="Logo03"
          />
          <img
            class="logo col-2"
            src="../assets/img/client-logo-04.png"
            alt="Logo04"
          />
          <img
            class="logo col-2"
            src="../assets/img/client-logo-05.png"
            alt="Logo05"
          />
          <img
            class="logo col-2"
            src="../assets/img/client-logo-06.png"
            alt="Logo06"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "JumbotronComponent",
};
</script>

<style lang="scss" scoped>
.jumbotron {
  .ff-btn {
    color: white;
    background-color: #1fad96;
    padding: 10px 20px;
    i {
      margin: 0px 10px;
    }
  }

  .row {
    margin-top: 50px;
  }
}
p:last-child {
  margin-top: 20px;
}
.logo {
  width: 75px;
  height: 50px;
}
</style>