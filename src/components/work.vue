<template>
  <div class="container pb-5">
    <div class="text-center maintext">
      <h1>Our Work</h1>
      <div>
        We are specialists in multi-use, sustainable exhibition stands and event
        environments.
      </div>
    </div>
  </div>
  <div class="container pb-5">
    <div class="neww row px-2">
      <div class="col-lg-4 px-2">
        <img src="@/assets/images/slide1.png" alt="" />
      </div>
      <div class="col-lg-4 px-2">
        <img src="@/assets/images/slide1.png" alt="" />
      </div>
      <div class="col-lg-4 px-2">
        <img src="@/assets/images/slide1.png" alt="" />
      </div>
      <div class="col-lg-4 px-2">
        <img src="@/assets/images/slide1.png" alt="" />
      </div>
      <div class="col-lg-4 px-2">
        <img src="@/assets/images/slide1.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Work",
  mounted() {
    // $("").slick({
    //   infinite: true,
    //   slidesToShow: 1,
    //   slidesToScroll: 1,
    // });
    $(".neww").slick({
      dots: false,
      arrows: false,
      infinite: true,
      speed: 300,
      slidesToShow: 3,
      slidesToScroll: 1,
      autoplay: true,
      autoplaySpeed: 2000,
      responsive: [
        {
          breakpoint: 1024,
          settings: {
            slidesToShow: 2,
            slidesToScroll: 1,
            infinite: true,
            dots: true,
          },
        },
        {
          breakpoint: 600,
          settings: {
            slidesToShow: 2,
            slidesToScroll: 1,
          },
        },
        {
          breakpoint: 480,
          settings: {
            slidesToShow: 1,
            slidesToScroll: 1,
          },
        },
        // You can unslick at a given breakpoint now by adding:
        // settings: "unslick"
        // instead of a settings object
      ],
    });
  },
};
</script>

<style lang="scss">
@import "@/assets/scss/work.scss";
</style>
