<template>
  <header>
    <div class="container d-flex justify-content-between align-items-center">
      <img class="col-2" src="../assets/img/dark-logo.png" alt="Logo" />

      <nav class="navbar navbar-expand-md" id="nav">
        <div class="container">
          <div class="collapse navbar-collapse">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li
                class="d-inline-block px-4"
                v-for="item in NavLink"
                :key="item.id"
              >
                {{ item.name }}
                <i class="fa-solid fa-angle-down"></i>
              </li>
              <li><i class="fa-solid fa-circle-user"></i></li>
            </ul>
            <form class="d-flex">
              <input
                class="form-control me-2"
                type="search"
                placeholder="Search..."
              />
              <i
                class="
                  align-self-center
                  color-green
                  fa-solid fa-magnifying-glass
                "
              ></i>
            </form>
          </div>
        </div>
      </nav>
    </div>
  </header>
</template>

<script>
import NavLink from "@/assets/data/NavLink.json";
export default {
  name: "HeaderComponent",
  data() {
    return {
      NavLink,
    };
  },
};
</script>

<style lang="scss" scoped>
header {
  padding: 10px;
  box-shadow: 0px 3px rgba(105, 105, 105, 0.1);
}
img {
  height: 30px;
  width: 15%;
}
form {
  margin-left: 15px;
}
</style>