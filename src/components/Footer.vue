<template>
  <div class="container-fluid black-bg">
    <div class="container text-center">
      <div class="row pt-5">
        <div class="col-12">
          <h5 class="footer-header">Evans Water Corporation</h5>
        </div>
      </div>
      <div class="row">
        <div class="col-12">
          <h5 class="footer-header">
            Contact:
            <a href="mailto:twploftus@gmail.com">twploftus@gmail.com</a>
          </h5>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss">
@import "../assets/scss/main.scss";
.black-bg {
  background-color: black;
  height: 15vh;
}

.footer-header {
  color: white;
  font-weight: 200;
}
</style>
