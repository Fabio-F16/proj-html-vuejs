<template>
  <div>
    <div class="container">
      <div class="row mt-5">
        <div class="col-12 text-center mb-5">
          <p>MAXCOACH AVAILABLE COURSES</p>
          <h2>
            Access <span class="color-green">Smart Tutoring</span> Program For
            Benefits
          </h2>
        </div>
        <div class="col-12 col-md-4">
          <img src="../assets/img/home-2-image-box-01.png" alt="ImageBox01" />
          <h5 class="mt-3">Customize Preferences</h5>
          <p>
            Learners are given the right arrange and customize their study
            schedule and timetable based on preference.
          </p>
          <a class="color-grey" href="#"
            >Start here <i class="fa-solid fa-arrow-right-long"></i
          ></a>
        </div>
        <div class="col-12 col-md-4">
          <img
            src="../assets/img/about-us-02-image-box-02.png"
            alt="ImageBox01"
          />
          <h5 class="mt-3">Cloud Storage</h5>
          <p>
            You can store online lesson via online cloud or download to your
            devixe and revise lesson on the way.
          </p>
          <a class="color-grey" href="#"
            >Get Free Quote <i class="fa-solid fa-arrow-right-long"></i
          ></a>
        </div>
        <div class="col-12 col-md-4">
          <img src="../assets/img/home-2-image-box-03.png" alt="ImageBox01" />
          <h5 class="mt-3">Customize Preferences</h5>
          <p>
            Learners are given the right arrange and customize their study
            schedule and timetable based on preference
          </p>
          <a class="color-grey" href="#"
            >Start Now<i class="fa-solid fa-arrow-right-long"></i
          ></a>
        </div>
      </div>
      <div class="row mt-5 py-5 align-items-center">
        <div class="col-12 col-md-7">
          <div
            class="
              video-poster
              d-flex
              justify-content-center
              align-items-center
            "
          >
            <img src="../assets/img/icon-youtube-play.png" alt="youtube" />
          </div>

          <img src="../assets/img/maxcoach-shape-05.png" alt="shape05" />
          <img src="../assets/img/maxcoach-shape-07.png" alt="shape07" />
        </div>
        <div class="col-12 col-md-5">
          <p>GET STARTED <span class="color-blue">EFFORTLESSLY</span></p>
          <h2>Enjoy Our <span class="color-green">Companionship</span></h2>
          <p>
            Sneek peek into what has in store for you on our online teaching and
            mentoring portal. Seek for some hidden hints of early-bird reward as
            well.
          </p>
          <a class="color-green" href="#"
            >Download free guidebook <i class="fa-solid fa-arrow-right-long"></i
          ></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SmartTutoringComponent",
};
</script>

<style lang="scss" scoped>
a {
  font-weight: bold;
  text-decoration: none;
  i {
    margin-left: 5px;
  }
}
a:hover {
  color: #1fad96;
}
p {
  color: #9ea4a5;
}
h2,
h5 {
  color: #3f3a64;
}
.video-poster {
  height: 400px;
  background-image: url("../assets/img/home-2-popup-video-poster.jpg");
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  z-index: 1;
  position: relative;
}

img[alt~="youtube"] {
  width: 10%;
  height: 15%;
  position: relative;
  z-index: 2;
  cursor: pointer;
}
img[alt~="shape05"] {
  width: 150px;
  height: 150px;
  position: relative;
  right: 50px;
  bottom: 220px;
}
img[alt~="shape07"] {
  width: 150px;
  height: 150px;
  position: relative;
  left: 50%;
  bottom: 100px;
}
</style>

