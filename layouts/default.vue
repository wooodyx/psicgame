<template>
  <div>
    <Navbar />
    <nuxt />
    <Footer />
  </div>
</template>
<script>
import Navbar from "~/components/navbar/navbar.vue";
import Footer from "~/components/footer/footer.vue";

export default {
  components: {
    Navbar,
    Footer
  }
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap");

* {
  font-family: "Poppins", sans-serif;
}

body {
  overflow-x: hidden;
}

/* width */
::-webkit-scrollbar {
  width: 0;
}
</style>
