<template>
  <NavBar/>
  <HeroSection/>
  <HardSkills/>
</template>

<script>
import NavBar from './components/NavigationBar.vue'
import HeroSection from './components/HeroSection.vue'
import HardSkills from './components/HardSkills.vue'


export default {
  name: 'App',
  components: {
    NavBar,
    HeroSection,
    HardSkills,
  }
}
</script>
<style src="./assets/styles.css"></style>
