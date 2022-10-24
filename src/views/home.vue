<template>
  <Herosection />
  <Bluestone />
  <Services />
  <Work />
  <Brands />
  <Blogs />
  <Contact />
  <Footer />
</template>

<script>
import Herosection from "../components/herosection.vue";
import Bluestone from "../components/bluestone.vue";
import Services from "../components/services.vue";
import Work from "../components/work.vue";
import Brands from "../components/brands.vue";
import Blogs from "../components/blogs.vue";
import Contact from "../components/contact.vue";
import Footer from "../components/footer.vue";
export default {
  name: "Home",
  components: {
    Herosection,
    Bluestone,
    Services,
    Work,
    Brands,
    Blogs,
    Contact,
    Footer,
  },
};
</script>

<style lang="scss" scoped></style>
