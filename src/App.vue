<template>
  <div id="app">
    <Navbar/>
    <Testimonials/>
    <Features/>
    <Newsletter/>
    <Footer year="2020"/>
  </div>
</template>

<script>
import Navbar from './components/navbar.vue'
import Testimonials from './components/testimonials.vue'
import Features from './components/features.vue'
import Newsletter from './components/newsletter.vue'
import Footer from './components/footer.vue'

export default {
  name: 'App',
  components: {
     Navbar,
    Testimonials,
    Features,
    Newsletter,
    Footer,
  }
}
</script>

<style>

</style>
