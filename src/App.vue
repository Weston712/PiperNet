<script>
import Footer from "./components/Footer.vue";
import Header from "./components/Header.vue";
import HeroImg from "./components/HeroImg.vue";
import Piper from "./components/Piper.vue";
import PiperCoin from "./components/PiperCoin.vue";
import TheProblem from "./components/TheProblem.vue";
import TheTeam from "./components/TheTeam.vue";

export default {
  components: { Header, Piper, TheProblem, HeroImg, PiperCoin, TheTeam, Footer },
};
</script>

<template>
  <div class="app">
    <Header />
    <Piper />
    <TheProblem />
    <HeroImg />
    <PiperCoin />
    <TheTeam />
    <Footer />
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  font-family: "Roboto";
}
</style>
