<template>
  <div class="container py-5">
    <div class="text-center">
      <h1>Latest Blogs</h1>
      <div>Our Latest Blogs/News</div>
    </div>
    <div class="row pt-5">
      <div class="col-lg-4">
        <div class="card rounded-0">
          <img
            src="@/assets/images/blog1.png"
            class="card-img-top rounded-0"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">
              <div class="d-flex justify-content-evenly">
                <div class="date">
                  <h1>30</h1>
                  <div>Mar</div>
                </div>
                <div class="ms-4">
                  Questions To Ask Yourself Before Renting Or Buying..
                </div>
              </div>
            </h5>
            <p class="card-text py-3">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
            <a href="#" class="text-decoration-none"
              ><button class="p-0 d-flex">
                <div class="">Read More</div>
                <i class="ri-arrow-right-line ms-2"></i></button
            ></a>
          </div>
        </div>
      </div>
      <div class="col-lg-4">
        <div class="card rounded-0">
          <img
            src="@/assets/images/blog2.png"
            class="card-img-top rounded-0"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">
              <div class="d-flex justify-content-evenly">
                <div class="date">
                  <h1>26</h1>
                  <div>Mar</div>
                </div>
                <div class="ms-4">
                  Salon VS Foire, quelle est la différence ?
                </div>
              </div>
            </h5>
            <p class="card-text py-3">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
            <a href="#" class="text-decoration-none"
              ><button class="p-0 d-flex">
                <div class="">Read More</div>
                <i class="ri-arrow-right-line ms-2"></i></button
            ></a>
          </div>
        </div>
      </div>
      <div class="col-lg-4">
        <div class="card rounded-0">
          <img
            src="@/assets/images/blog3.png"
            class="card-img-top rounded-0"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">
              <div class="d-flex justify-content-evenly">
                <div class="date">
                  <h1>21</h1>
                  <div>Mar</div>
                </div>
                <div class="ms-4">
                  B2B Marketing Trends to ensure a successful exhi...
                </div>
              </div>
            </h5>
            <p class="card-text py-3">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
            <a href="#" class="text-decoration-none"
              ><button class="p-0 d-flex">
                <div class="">Read More</div>
                <i class="ri-arrow-right-line ms-2"></i></button
            ></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Blogs",
};
</script>

<style lang="scss" scoped>
@import "@/assets/scss/blogs.scss";
</style>
