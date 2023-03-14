<script>
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import sectionInfoMore from './components/sectionInfoMore.vue'
import sectionExplore from './components/sectionExplore.vue'
import sectionInfo from './components/sectionInfo.vue'

export default {
  components: {
    Header,
    Hero,
    sectionInfoMore,
    sectionExplore,
    sectionInfo,
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



</template>

<style lang="scss">



</style>