<template>
  <div id="app">
    <Header />
    <Slider />
    <NewReleases />
    <RecommendWatch />
    <Footer />
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from './components/layout/Header.vue'
import Slider from './components/Slider.vue'
import NewReleases from './components/NewReleases.vue'
import RecommendWatch from './components/RecommendWatch.vue'
import Footer from './components/layout/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Slider,
    NewReleases,
    RecommendWatch,
    Footer
  }
}
</script>

<style>

</style>
