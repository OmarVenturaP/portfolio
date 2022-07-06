<template>
  <NavBar/>
  <HeroSection/>
</template>

<script>
import NavBar from './components/NavigationBar.vue'
import HeroSection from './components/HeroSection.vue'


export default {
  name: 'App',
  components: {
    NavBar,
    HeroSection,
  }
}
</script>
<style src="./assets/styles.css"></style>
