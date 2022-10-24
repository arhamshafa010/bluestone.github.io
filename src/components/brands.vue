<template>
  <section>
    <div class="container py-5">
      <div class="row">
        <div class="col-lg-6 first">
          <div>
            <img
              class="position-absolute img1"
              src="@/assets/images/colons.png"
              alt=""
            />
          </div>
          <div class="sliding text-light px-5">
            <div class="slider-items pb-2">
              <h2>You are amazing! You worked so hard for Cady's wedding.</h2>
              <p>
                You are amazing! You worked so hard for Cady's wedding. You had
                every little detail under control you need to run my life!
              </p>
              <h2 class="name">David Warner - Founder</h2>
              <div><img src="@/assets/images/first.png" /></div>
            </div>
            <!-- <div class="slider-items pb-2">
              <h2>You are amazing! You worked so hard for Cady's wedding.</h2>
              <p>
                You are amazing! You worked so hard for Cady's wedding. You had
                every little detail under control you need to run my life!
              </p>
              <h2 class="name">Jasmeet Kaur</h2>
              <div><img src="@/assets/images/second.png" /></div>
            </div> -->
            <!-- <div class="slider-items pb-2">
              <h2>You are amazing! You worked so hard for Cady's wedding.</h2>
              <p>
                You are amazing! You worked so hard for Cady's wedding. You had
                every little detail under control you need to run my life!
              </p>
              <h2 class="name">David Becham</h2>
              <div><img src="@/assets/images/third.png" /></div>
            </div> -->
            <!-- <div class="slider-items pb-2">
              <h2>You are amazing! You worked so hard for Cady's wedding.</h2>
              <p>
                You are amazing! You worked so hard for Cady's wedding. You had
                every little detail under control you need to run my life!
              </p>
              <h2 class="name">Sardar Bahdur</h2>
              <div><img src="@/assets/images/fouth.png" /></div>
            </div> -->
          </div>
        </div>
        <div class="col-lg-6">
          <div class="d-flex justify-content-evenly">
            <div>
              <img class="w-75" src="@/assets/images/logo1.png" alt="" />
            </div>
            <div>
              <img class="w-75" src="@/assets/images/logo2.png" alt="" />
            </div>
            <div>
              <img class="w-75" src="@/assets/images/logo3.png" alt="" />
            </div>
          </div>
          <div class="d-flex mt-5 justify-content-evenly">
            <div>
              <img class="w-75" src="@/assets/images/logo4.png" alt="" />
            </div>
            <div>
              <img class="w-75" src="@/assets/images/logo5.png" alt="" />
            </div>
          </div>
          <div class="d-flex mt-5 justify-content-evenly">
            <div>
              <img class="w-75" src="@/assets/images/logo6.png" alt="" />
            </div>
            <div>
              <img class="w-75" src="@/assets/images/logo7.png" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Brands",
  // mounted() {
  //   $(".sliding").slick({
  //     dots: false,
  //     arrows: false,
  //     infinite: true,
  //     speed: 300,
  //     slidesToShow: 1,
  //     slidesToScroll: 1,
  //     autoplay: true,
  //     autoplaySpeed: 2000,
  //     responsive: [
  //       {
  //         breakpoint: 1024,
  //         settings: {
  //           slidesToShow: 1,
  //           slidesToScroll: 1,
  //           infinite: true,
  //           dots: true,
  //         },
  //       },
  //       {
  //         breakpoint: 600,
  //         settings: {
  //           slidesToShow: 1,
  //           slidesToScroll: 1,
  //         },
  //       },
  //       {
  //         breakpoint: 480,
  //         settings: {
  //           slidesToShow: 1,
  //           slidesToScroll: 1,
  //         },
  //       },
  //       // You can unslick at a given breakpoint now by adding:
  //       // settings: "unslick"
  //       // instead of a settings object
  //     ],
  //   });
  // },
};
</script>

<style lang="scss" scoped>
@import "@/assets/scss/brand.scss";
</style>
