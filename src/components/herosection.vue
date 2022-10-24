<template>
  <section class="overflow-hidden">
    <div class="container">
      <div class="row">
        <div class="col-lg-4 bg">
          <div class="text-light text1 py-5">
            <h1>Design.</h1>
            <h1>Create.</h1>
            <h1>and Build.</h1>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum
              nihil, harum deleniti nemo hic velit doloribus ut veritatis rem
              repellat iusto, assumenda sapiente corporis labore maiores
              quibusdam
            </p>
            <button class="d-flex">
              <div class="ms-3">Start Your Project</div>
              <i class="ri-arrow-right-line ms-3"></i>
            </button>
          </div>
        </div>
        <div class="col-lg-8 p-0">
          <div class="full-width">
            <img class="width" src="@/assets/images/heroimg.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Herosection",
};
</script>

<style lang="scss" scoped>
@import "@/assets/scss/herosection.scss";
</style>
