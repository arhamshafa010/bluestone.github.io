<template>
  <section>
    <div class="container py-5">
      <div class="row">
        <div class="col-lg-5">
          <h1>Do you have</h1>
          <h1>a project?</h1>
          <h1>Lets Talk.</h1>
          <p class="pt-2">
            Please fill in the details and we will be in touch shortly or send
            us email or Call us
          </p>
          <div class="pt-3 email">sales@bluestoneworldwide.com</div>
          <div class="pt-3 number">99251 77600</div>
        </div>
        <div class="col-lg-7 paddingtp">
          <div class="container">
            <div class="col-lg-12">
              <h5 class="text-center">Complete the form below...</h5>
            </div>
            <div class="row pt-5">
              <div class="col-lg-6">
                <input type="text" name="" id="" placeholder="Full Name" />
              </div>
              <div class="col-lg-6 paddingtp">
                <input
                  type="text"
                  name=""
                  id=""
                  placeholder="Your Company Name"
                />
              </div>
            </div>
            <div class="row pt-5">
              <div class="col-lg-6">
                <input
                  type="email"
                  name=""
                  id=""
                  placeholder="Business email"
                />
              </div>
              <div class="col-lg-6 paddingtp">
                <input type="number" name="" id="" placeholder="Phone Number" />
              </div>
            </div>
            <div class="row pt-5">
              <div class="col-lg-6">
                <select
                  class="form-select p-0"
                  aria-label="Default select example"
                >
                  <option selected>Select your Country</option>
                  <option value="1">USA</option>
                  <option value="2">Canada</option>
                  <option value="3">Pakistan</option>
                </select>
              </div>
              <div class="col-lg-6 paddingtp">
                <input
                  type="text"
                  name=""
                  id=""
                  placeholder="What services you are interested in"
                />
              </div>
            </div>
            <div class="row pt-5">
              <div class="col-lg-12">
                <input type="text" name="" id="" placeholder="Message" />
              </div>
            </div>
            <div class="row pt-5">
              <div class="col-lg-12">
                <a href="/"><button>Send a request</button></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Contact",
};
</script>

<style lang="scss" scoped>
@import "@/assets/scss/contact.scss";
</style>
