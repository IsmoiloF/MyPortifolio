<template >
  <div>
    <Header />


    <HomeView />

    <Footer />
  </div>
</template>
<script>
import Header from './components/Header/Header.vue';
import Footer from './components/Footer/Footer.vue';
import HomeView from "./views/HomeView.vue"
export default {
  name:"App",
  components:{
    Header,
    Footer,
    HomeView
  }
}
</script>
<style >
  
</style>