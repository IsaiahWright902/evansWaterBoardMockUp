<template>
  <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container-fluid pt-3">
      <!-- <a class="navbar-brand" href="#">Isaiah Wright</a> -->
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mb-2 mb-lg-0"></ul>
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="#">News</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="#">Water Tests</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
import { computed, onMounted, reactive } from "vue";
export default {
  name: "Navbar",
  setup() {
    const state = reactive({});
    return {
      state,
    };
  },
};
</script>

<style lang="scss">
@import "../assets/scss/main.scss";
.navbar-brand {
  font-family: "Montserrat", sans-serif;
  font-size: 35px;
  font-weight: 400;
  margin-left: 50px;
  transition: all 1s ease-in-out;
  &:hover {
    text-decoration: underline black;
  }
  @include respond(tablet) {
    margin-left: 10px;
  }
  @include respond(phone) {
    margin-left: 0;
  }
}

.navbar {
  background: transparent;
}

.navbar-nav > .nav-item {
  margin-left: 15px;
  margin-right: 50px;
  @include respond(tablet) {
    margin-right: 15px;
  }
  @include respond(phone) {
    margin-left: 0;
  }
}

.nav-item {
  font-size: 22px;
  font-weight: 500;
}

.nav-link {
  font-family: "Montserrat", sans-serif;

  color: rgb(192, 192, 192) !important;
  transition: all 0.7s;
  &:hover {
    color: white !important;
  }
}
</style>
