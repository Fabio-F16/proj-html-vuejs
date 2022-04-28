<template>
  <div>
    <div class="container">
      <div class="row">
        <div class="col-12 col-md-3 text-center">
          <div class="box">
            <h6>
              Successfully <br />
              trained
            </h6>
            <span class="number color-green">1790</span>
            <p class="color-grey">ENROLLED LEANERS</p>
          </div>
        </div>
        <div class="col-12 col-md-3 text-center">
          <div class="box">
            <h6>
              Proudly <br />
              Received
            </h6>
            <span class="number color-green">19</span>
            <p class="color-grey">COUNTRYWIDE AWARDS</p>
          </div>
        </div>
        <div class="col-12 col-md-3 text-center">
          <div class="box">
            <h6>
              Firmly <br />
              Established
            </h6>
            <span class="number color-green">24</span>
            <p class="color-grey">LOCAL BRANCHES</p>
          </div>
        </div>
        <div class="col-12 col-md-3 text-center">
          <div class="box">
            <h6>
              Getting <br />
              Featured on
            </h6>
            <span class="number color-green">1090</span>
            <p class="color-grey">BLOG POSTS</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "StatisticsComponent",
};
</script>

<style lang="scss" scoped>
h6 {
  color: #3f3a64;
}
.number {
  font-size: 2.5rem;
  font-weight: bold;
}
.box {
  display: block;
  border-left: 1px solid;
  border-right: 1px solid;
  border-color: #f6f3f5;
  padding: 75px 0px;
  margin: 0px;
  p {
    font-size: 0.8rem;
  }
}
</style>