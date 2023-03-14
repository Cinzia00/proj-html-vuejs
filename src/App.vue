<script>
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import sectionInfoMore from './components/sectionInfoMore.vue'
import sectionExplore from './components/sectionExplore.vue'
import sectionInfo from './components/sectionInfo.vue'
import sectionUpcoming from './components/sectionUpcoming.vue'
import sectionTestimonial from './components/sectionTestimonial.vue'

export default {
  components: {
    Header,
    Hero,
    sectionInfoMore,
    sectionExplore,
    sectionInfo,
    sectionUpcoming,
    sectionTestimonial,
  },
  data() {
    return {

    }
  }

}
</script>

<template>
  <Header />
  <Hero />
  <sectionInfoMore />
  <sectionExplore />
  <sectionInfo />
  <sectionTestimonial />



</template>

<style lang="scss">



</style>