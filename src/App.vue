<template>
  <HeaderLorem/>
  <SectionOne/>
  <SectionTwo/>
  <SectionThree/>
  <SectionFour/>
</template>

<script>
import HeaderLorem from './components/HeaderLorem.vue';
import SectionOne from './views/SectionOne.vue';
import SectionTwo from './views/SectionTwo.vue';
import SectionThree from './views/SectionThree.vue';
import SectionFour from './views/SectionFour.vue';
export default {
  name: 'App',
  components: {
    HeaderLorem,
    SectionOne,
    SectionTwo,
    SectionThree,
    SectionFour
  }
}
</script>

<style>
</style>
