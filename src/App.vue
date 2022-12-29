<template>
  <div class="app">
    <Navbar />
    <Header />
    <Texnologie />
  </div>
  <Cards />
  <div class="app">
    <View />
    <CardInfo />
    <Tech />
    <Abus />
  </div>
</template>
<script>
import Abus from "./components/Obucheniye.vue"
import CardInfo from "./components/CardInfo.vue"
import View from './components/View.vue'
import Navbar from './components/Navbar.vue';
import Header from "./components/Header.vue"
import Texnologie from "./components/Texnologie.vue"
import Cards from "./components/Cards.vue"
import Tech from "./components/Tech.vue"
import AOS from "aos"
import "aos/dist/aos.css"

export default {
  created() {
    AOS.init()
  },
  components: {
    View,
    Navbar,
    Header,
    Texnologie,
    Cards,
    CardInfo,
    Tech,
    Abus,
  }
}
</script>
<style>
.app {
  padding: 0px 200px;
  font-family: "Poppins", sans-serif;
}
</style>