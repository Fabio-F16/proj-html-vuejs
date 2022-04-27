<template>
  <div class="bg-lightgrey">
    <div class="container py-5">
      <div class="row justify-content-between">
        <div class="col-12 col-md-4">
          <p class="color-grey">ENJOYABLE INSIGHTS</p>
          <h4>Most Viewed <span class="color-green">Best Blogs</span></h4>
          <ul>
            <li>
              <i class="fa-solid fa-arrow-right-long"></i>Become a Better
              Blogger: Content Planning
            </li>
            <li>
              <i class="fa-solid fa-arrow-right-long"></i>Promoting Your Online
              Business on Pintrest
            </li>
            <li>
              <i class="fa-solid fa-arrow-right-long"></i>Gamification and
              Game-Based Learning
            </li>
            <li>
              <i class="fa-solid fa-arrow-right-long"></i>Designing on Online
              Course from Expert's perspective
            </li>
            <li>
              <i class="fa-solid fa-arrow-right-long"></i>Why Online Courses Are
              the Future of Education
            </li>
          </ul>
        </div>
        <div class="col-12 col-md-3">
          <div class="card" style="width: 18rem">
            <img
              src="../assets/img/artist-blog-03-480x352.jpeg"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body">
              <p>ARTIST</p>
              <h5 class="card-title">
                Brush Strokes Energize Trees in Paintings
              </h5>
              <div class="d-flex gap-3">
                <div class="card-info">
                  <i class="fa-solid fa-calendar color-grey"></i>
                  <span>May 15, 2020</span>
                </div>
                <div class="card-info">
                  <i class="fa-solid fa-eye color-grey"></i>
                  <span>688 views</span>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-3">
          <div class="card" style="width: 18rem">
            <img
              src="../assets/img/artist-blog-01-480x352.jpg"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body">
              <p>ARTIST</p>
              <h5 class="card-title">
                Pocket-sized Notebooks Hold Miniature Paintings
              </h5>
              <div class="d-flex gap-3">
                <div class="card-info">
                  <i class="fa-solid fa-calendar color-grey"></i>
                  <span>May 15, 2020</span>
                </div>
                <div class="card-info">
                  <i class="fa-solid fa-eye color-grey"></i>
                  <span>603 views</span>
                </div>
              </div>
            </div>
          </div>
          <!-- <img src="../assets/img/artist-blog-03-480x352.jpeg" alt="Artist01" />
          <p>ARTIST</p>
          <h6>Brush Strokes Energize Trees in Paintings</h6> -->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BlogsComponent",
};
</script>

<style lang="scss" scoped>
ul {
  padding: 0;
  list-style-type: none;
  //   color: #9ea4a5;
  margin-top: 20px;

  li {
    margin-top: 10px;
    font-size: 0.9rem;
    font-weight: bold;
  }
}
i {
  margin-right: 10px;
}
.card-info {
  margin-top: 10px;
}
.card p,
.card span {
  font-size: 0.9rem;
  color: #9ea4a5;
}
</style>