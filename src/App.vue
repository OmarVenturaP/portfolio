<template>
  <NavBar/>
  <HeroSection/>
  <HardSkills/>
  <ProjectsPortfolio/>
  <VocationalTraining/>
  <AboutMe/>
</template>

<script>
import NavBar from './components/NavigationBar.vue'
import HeroSection from './components/HeroSection.vue'
import HardSkills from './components/HardSkills.vue'
import ProjectsPortfolio from './components/ProjectsPortfolio.vue'
import VocationalTraining from './components/VocationalTraining.vue'
import AboutMe from './components/AboutMe.vue'


export default {
  name: 'App',
  components: {
    NavBar,
    HeroSection,
    HardSkills,
    ProjectsPortfolio,
    VocationalTraining,
    AboutMe
}
}
</script>
<style src="./assets/css/styles.css"></style>
