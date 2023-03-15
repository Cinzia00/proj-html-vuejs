<script>
import HeaderApp from './components/HeaderApp.vue'
import Hero from './components/Hero.vue'
import sectionInfoMore from './components/sectionInfoMore.vue'
import sectionExplore from './components/sectionExplore.vue'
import sectionInfo from './components/sectionInfo.vue'
import sectionUpcoming from './components/sectionUpcoming.vue'
import sectionTestimonial from './components/sectionTestimonial.vue'
import footerApp from './components/footerApp.vue'

export default {
  components: {
    HeaderApp,
    Hero,
    sectionInfoMore,
    sectionExplore,
    sectionInfo,
    sectionUpcoming,
    sectionTestimonial,
    footerApp
  },
  data() {
    return {

    }
  }

}
</script>

<template>
  <HeaderApp />
  <main>
    <Hero />
    <sectionInfoMore />
    <sectionExplore />
    <sectionInfo />
    <sectionUpcoming />
    <sectionTestimonial />
  </main>
  <footerApp />



</template>

<style lang="scss">



</style>