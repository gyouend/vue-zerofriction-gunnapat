<template>
  <HeaderLorem/>
  <SectionOneVue/>
</template>

<script>
import HeaderLorem from './components/HeaderLorem.vue';
import SectionOneVue from './components/SectionOne.vue';
export default {
  name: 'App',
  components: {
    HeaderLorem,
    SectionOneVue
  }
}
</script>

<style>
</style>
