<template>
  <div class="bg-lightgrey py-5">
    <div class="container-xl">
      <div class="row justify-content-between">
        <div class="col-12 text-center">
          <p>GREAT WORDS ABOUT MAXCOACH</p>
          <h2>Our <span class="color-green">top learners'</span> verbatim</h2>
        </div>

        <div class="review col-12 col-md-4 bg-lightgrey py-4">
          <h6>It's a choice of qulity for people with special needs</h6>
          <p>
            I'm a very strict person so I require everything to be organized and
            neat. Then, I'll be able to make things right and shine. MaxCoach
            guys just got me.
          </p>
          <div class="d-flex align-items-center">
            <img
              class="rounded-circle w-25"
              src="../assets/img/testimonial-avata-03.jpg"
              alt=""
            />
            <div class="col-6 ms-4">
              <h6>FLORENCE THEMES</h6>
              <p>/Multimedia admin</p>
            </div>
          </div>
        </div>
        <div class="review col-12 col-md-4 bg-lightgrey py-4">
          <h6>High level of efficiency and scientific teaching methods</h6>
          <p>
            I am free to learn at my own pace, follow my own schedule and choose
            the subject I want to learn from the syllabus. Great study portal
            for people like me.
          </p>
          <div class="d-flex align-items-center">
            <img
              class="rounded-circle w-25"
              src="../assets/img/testimonial-avata-02.jpg"
              alt=""
            />
            <div class="col-6 ms-4">
              <h6>MINA HOLLACE</h6>
              <p>/Freelancer</p>
            </div>
          </div>
        </div>
        <div class="review col-12 col-md-4 bg-lightgrey py-4">
          <h6>
            Professional team of specialists and passionate mentors at reach
          </h6>
          <p>
            I need to get a certification for English proficiency and MaxCoach
            is my best choice. Their tutors are smart and professional when
            dealing with students.
          </p>
          <div class="d-flex align-items-center">
            <img
              class="rounded-circle w-25"
              src="../assets/img/testimonial-avata-04.jpg"
              alt=""
            />
            <div class="col-6 ms-4">
              <h6>MADLEY PONDORS</h6>
              <p>/IT Specialist</p>
            </div>
          </div>
        </div>
      </div>
      <div class="container">
        <div class="row py-4">
          <div class="col-12 col-md-2">
            <img src="../assets/img/maxcoach-shape-01.png" alt="shape01" />
          </div>
          <div class="col-12 col-md-8 text-center">
            <h6>
              Start today for getting
              <span class="color-green">Online Certification</span>
            </h6>
            <h3>You can e your own guiding star with our help!</h3>
            <button class="btn w-50 ff-btn mt-4">Get started now</button>
          </div>
          <div class="col-12 col-md-2">
            <img src="../assets/img/maxcoach-shape-02.png" alt="shape02" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ReviewComponent",
};
</script>

<style lang="scss" scoped>
.review:hover {
  background-color: white;
}
h2,
h6,
h3 {
  color: #3f3a64;
}
p {
  color: #9ea4a5;
}
</style>