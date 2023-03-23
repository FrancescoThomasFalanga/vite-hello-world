<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";
import Navbar from "./components/Navbar.vue";

export default {
  data() {
    return {

    }
  },

  components: {
    AppTitle,
    AppHero,
    Navbar,
  },

}
</script>



<template>

  <Navbar></Navbar>

  <AppHero></AppHero>

  <AppTitle></AppTitle>

</template>



<style></style>