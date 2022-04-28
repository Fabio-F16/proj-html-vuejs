<template>
  <div>
    <div class="jumbotron py-5">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-12 col-md-6">
            <h1 class="color-blue">Distant learning for further expansion</h1>
            <p class="color-grey">
              Learning is a life-long journey that in fact we never find the
              terminate stop. Stop searching, enjoy the process
            </p>
            <button class="btn ff-btn">
              <i class="fa-solid fa-download"></i> Download free guide
            </button>
            <p class="color-grey">
              Have questions?
              <a class="color-green" href="#"
                >Get Free Sample <i class="fa-solid fa-arrow-right-long"></i
              ></a>
            </p>
          </div>
          <div class="pagination col-12 col-md-6">
            <img
              class="pagination rounded-circle"
              src="../assets/img/about-me-profile.jpg"
              alt="aboutMe"
            />
            <img src="../assets/img/maxcoach-shape-02.png" alt="shape02" />
            <img src="../assets/img/maxcoach-shape-07.png" alt="shape07" />
            <img src="../assets/img/maxcoach-shape-08.png" alt="shape08" />
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
.row {
  margin-top: 50px;
}

p:last-child {
  margin-top: 20px;
}

a {
  text-decoration: none;
  font-weight: bold;
  padding-bottom: 5px;
  border-bottom: 1px solid lightgrey;
}

img[alt~="aboutMe"] {
  position: relative;
  z-index: 100;
}
img[alt~="shape02"] {
  width: 150px;
  height: 150px;
  position: relative;
  right: 100px;
}
img[alt~="shape07"] {
  width: 150px;
  height: 150px;
  position: relative;
  right: 300px;
  top: 350px;
}
img[alt~="shape08"] {
  width: 150px;
  height: 150px;
  position: relative;
  right: 140%;
  top: 150px;
}
.logo {
  width: 75px;
  height: 50px;
}
</style>