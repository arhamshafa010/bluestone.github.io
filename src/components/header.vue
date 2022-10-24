<template>
  <section>
    <div class="container text-light py-2">
      <div class="row">
        <div class="col-md-6 col-sm-6">
          <div class="d-flex one">
            <div class="ind">India</div>
            <div class="eup">Europe</div>
            <div class="us">USA</div>
          </div>
        </div>
        <div class="col-md-6 col-sm-6 d-flex justify-content-end two">
          <div class="d-flex">
            <i class="ri-phone-line"></i>
            <div class="ind">+9292929292</div>
          </div>
          <div class="d-flex ms-2">
            <i class="ri-mail-line me-1"></i>
            <div class="ind">info@gamil.com</div>
          </div>
          <div class="d-flex ms-2">
            <i class="ri-twitter-line me-1"></i>
            <i class="ri-facebook-line me-1"></i>
            <i class="ri-youtube-line"></i>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
@import "@/assets/scss/header.scss";
</style>
