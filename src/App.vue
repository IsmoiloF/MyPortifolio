<template>
  <div class="">
    <Header />

    <RouterView />

    <Footer />
  </div>
</template>
<script>
import Header from "./components/Header/Header.vue";
import Footer from "./components/Footer/Footer.vue";
import HomeView from "./views/HomeView.vue";
import { RouterView } from "vue-router";
export default {
  name: "App",
  components: {
    Header,
    Footer,
    HomeView,
    RouterView,
  },
};
</script>
<style></style>
