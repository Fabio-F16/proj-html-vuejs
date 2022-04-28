<template>
  <section class="bg-lightgrey py-5">
    <div class="container">
      <div class="row">
        <div class="col-12 text-center">
          <p class="color-grey">STIMULATED TO LEARN?</p>
          <h2 class="color-blue">Featured Online Courses</h2>
        </div>
        <div class="col-12 col-md-6 d-flex mt-5 align-items-center">
          <img
            class="img rounded-circle"
            src="../assets/img/course-02-480x298.jpg"
            alt=""
          />
          <div class="info">
            <p>$40.00</p>
            <h6>Learning to write as a professional author</h6>
            <span><i class="fa-solid fa-file-lines"></i> 20 Lesson</span>
            <span><i class="fa-solid fa-user"></i> 20 Students</span>
          </div>
        </div>
        <div class="col-12 col-md-6 d-flex mt-5 align-items-center">
          <img
            class="img rounded-circle"
            src="../assets/img/stock-full-hd-03-480x298.jpg"
            alt=""
          />
          <div class="info">
            <p>Free</p>
            <h6>Customer-centric Info-tech strategies</h6>
            <span><i class="fa-solid fa-file-lines"></i> 24 Lesson</span>
            <span><i class="fa-solid fa-user"></i> 769 Students</span>
          </div>
        </div>
        <div class="col-12 col-md-6 d-flex mt-5 align-items-center">
          <img
            class="img rounded-circle"
            src="../assets/img/stock-full-hd-04-480x298.jpg"
            alt=""
          />
          <div class="info">
            <p>$19.00</p>
            <h6>Open Programming Courses for Everyone: Python</h6>
            <span><i class="fa-solid fa-file-lines"></i> 17 Lesson</span>
            <span><i class="fa-solid fa-user"></i> 62 Students</span>
          </div>
        </div>
        <div class="col-12 col-md-6 d-flex mt-5 align-items-center">
          <img
            class="img rounded-circle"
            src="../assets/img/stock-full-hd-06-480x298.jpg"
            alt=""
          />
          <div class="info">
            <p>$26.00</p>
            <h6>Academic Listening and Note-taking</h6>
            <span><i class="fa-solid fa-file-lines"></i> 14 Lesson</span>
            <span><i class="fa-solid fa-user"></i> 67 Students</span>
          </div>
        </div>
        <div class="col-12 col-md-6 d-flex mt-5 align-items-center">
          <img
            class="img rounded-circle"
            src="../assets/img/course-featured-image-01-480x298.jpg"
            alt=""
          />
          <div class="info">
            <p>$39.00</p>
            <h6>Master jQuery in a Short Period of Time</h6>
            <span><i class="fa-solid fa-file-lines"></i> 14 Lesson</span>
            <span><i class="fa-solid fa-user"></i> 67 Students</span>
          </div>
        </div>
        <div class="col-12 col-md-6 d-flex mt-5 align-items-center">
          <img
            class="img rounded-circle"
            src="../assets/img/stock-full-hd-05-480x298.jpg"
            alt=""
          />
          <div class="info">
            <p>$59.00</p>
            <h6>Introduction to Javascript to Beginners</h6>
            <span><i class="fa-solid fa-file-lines"></i> 14 Lesson</span>
            <span><i class="fa-solid fa-user"></i> 67 Students</span>
          </div>
        </div>
      </div>
      <div class="col-12 text-center">
        <button class="btn ff-btn">
          <a href="#nav"
            >View All Courses <i class="fa-solid fa-arrow-right-long"></i
          ></a>
        </button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "CoursesComponent",
};
</script>

<style lang="scss" scoped>
.img {
  width: 150px;
  height: 150px;
  text-align: center;
}
.info {
  margin-left: 25px;
  h6 {
    color: #3f3a64;
  }
  h6:hover {
    color: #1fad96;
    cursor: pointer;
  }
  p:first-child {
    color: #1fad96;
    font-weight: bold;
  }
  span {
    color: #9ea4a5;
    font-size: 0.8rem;
    margin-right: 25px;
  }
}
.ff-btn {
  background-color: #1fad96;
  padding: 10px 20px;
  margin-top: 35px;
  a {
    color: white;
    text-decoration: none;
  }
}
</style>