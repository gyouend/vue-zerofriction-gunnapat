<template>
  <HeaderLorem/>
  <SectionOne/>
  <SectionTwo/>
  <SectionThree/>
  <SectionFour/>
</template>

<script>
import HeaderLorem from './components/HeaderLorem.vue';
import SectionOne from './components/views/SectionOne.vue';
import SectionTwo from './components/views/SectionTwo.vue';
import SectionThree from './components/views/SectionThree.vue';
import SectionFour from './components/views/SectionFour.vue';
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
