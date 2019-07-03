<template>
  <div id="app">
    <Hero/>
    <HowItWorks/>
    <Features/>
    <Suppliers/>
    <Footer/>
  </div>
</template>

<script>
import Hero from './components/Hero'
import HowItWorks from './components/HowItWorks'
import Features from './components/Features'
import Suppliers from './components/Suppliers'
import Footer from './components/Footer'

export default {
  name: 'app',
  components: {
    Hero,
    HowItWorks,
    Features,
    Suppliers,
    Footer
  }
}
</script>

<style>
* {
  font-family: 'Nunito', sans-serif;
}
h1 {
  font-family: 'Bree Serif', serif;
}
html {
  scroll-behavior: smooth;
}
</style>
