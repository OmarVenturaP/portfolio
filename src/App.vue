<template>
  <NavBar/>
  <HeroSection/>
  <HardSkills/>
  <ProjectsPortfolio/>
  <VocationalTraining/>
  <AboutMe/>
  <MyCertifications/>
  <ContactForm/>
  <FooterPage/>
  <PortfolioModal1/>
  <PortfolioModal2/>
  <PortfolioModal3/>
  <PortfolioModal4/>
  <PortfolioModal5/>
  <PortfolioModal6/>
  <SoftSkills/>
</template>

<script>
import NavBar from './components/NavigationBar.vue'
import HeroSection from './components/HeroSection.vue'
import HardSkills from './components/HardSkills.vue'
import ProjectsPortfolio from './components/ProjectsPortfolio.vue'
import VocationalTraining from './components/VocationalTraining.vue'
import AboutMe from './components/AboutMe.vue'
import MyCertifications from './components/MyCertifications.vue'
import ContactForm from './components/ContactForm.vue'
import FooterPage from './components/FooterPage.vue'
import PortfolioModal1 from './components/PortfolioModal/PortfolioModal1.vue'
import PortfolioModal2 from './components/PortfolioModal/PortfolioModal2.vue'
import PortfolioModal3 from './components/PortfolioModal/PortfolioModal3.vue'
import PortfolioModal4 from './components/PortfolioModal/PortfolioModal4.vue'
import PortfolioModal5 from './components/PortfolioModal/PortfolioModal5.vue'
import PortfolioModal6 from './components/PortfolioModal/PortfolioModal6.vue'
import SoftSkills from './components/SoftSkills.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    HeroSection,
    HardSkills,
    ProjectsPortfolio,
    VocationalTraining,
    AboutMe,
    MyCertifications,
    ContactForm,
    FooterPage,
    PortfolioModal1,
    PortfolioModal2,
    PortfolioModal3,
    PortfolioModal4,
    PortfolioModal5,
    PortfolioModal6,
    SoftSkills,
}
}
</script>
<style src="./assets/css/styles.css"> </style>
