<template>
  <section>
    <div class="container p-0">
      <nav class="navbar navbar-expand-lg navbar-light">
        <div class="container-fluid">
          <router-link class="w-50" to="/"
            ><img
              class="logo w-50 img-fluid"
              src="@/assets/images/logo.png"
              alt="logo"
          /></router-link>
          <button
            class="navbar-toggler shadow-none"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div
            class="collapse navbar-collapse justify-content-end"
            id="navbarNav"
          >
            <ul class="navbar-nav">
              <li class="nav-item">
                <router-link
                  :to="{ name: 'home' }"
                  class="nav-link"
                  aria-current="page"
                  >Home</router-link
                >
              </li>
              <li class="nav-item">
                <router-link
                  :to="{ name: 'about' }"
                  class="nav-link"
                  aria-current="page"
                  >Company</router-link
                >
              </li>
              <li class="nav-item dropdown dpmain">
                <a
                  class="nav-link dropdown-toggle dpmain"
                  href="#"
                  id="navbarDropdown"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  Services
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li><hr class="dropdown-divider" /></li>
                  <li>
                    <a class="dropdown-item" href="#">Something else here</a>
                  </li>
                </ul>
              </li>
              <li class="nav-item">
                <router-link to="/about" class="nav-link" aria-current="page"
                  >Exhibitions</router-link
                >
              </li>
              <li class="nav-item">
                <router-link to="/about" class="nav-link" aria-current="page"
                  >Our Work</router-link
                >
              </li>
              <li class="nav-item">
                <router-link to="/about" class="nav-link" aria-current="page"
                  >Blogs</router-link
                >
              </li>
              <li class="nav-item">
                <router-link to="/about" class="nav-link" aria-current="page"
                  >Resource</router-link
                >
              </li>
              <li class="nav-item">
                <router-link to="/about" class="nav-link" aria-current="page"
                  >Contact</router-link
                >
              </li>
              <li class="nav-item">
                <router-link to="/" class="nav-link" aria-current="page"
                  ><button class="btn1">Get a Quote</button></router-link
                >
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </section>
  <router-view :key="$route.fullPath"></router-view>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style lang="scss" scoped>
@import "@/assets/scss/navbar.scss";
</style>
