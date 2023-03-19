<template>
  <HeaderLorem/>
  <SectionOne/>
  <SectionTwo/>
  <SectionThree/>
  <SectionFour/>
</template>

<script>
import HeaderLorem from './components/HeaderLorem.vue';
import SectionOne from './components/SectionOne.vue';
import SectionTwo from './components/SectionTwo.vue';
import SectionThree from './components/SectionThree.vue';
import SectionFour from './components/SectionFour.vue';
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
