<template>
  <div class="header-position">
    <GreenDinosaur />
    <span class="title common-style">LOREM</span>
    <span class="second-title common-style">IPSUM</span>
    <span class="sub-title">LOREM</span>
    <span class="sub-title">LOREM<ArrowDownIconVue class="arrow-down" /></span>
    <span class="sub-title">LOREMIPSUM</span>
    <span class="sub-title">LOREM & IPSUM</span>
    <span class="sub-title">LOREM</span>
  </div>
</template>

<script>
import ArrowDownIconVue from "./icons/ArrowDownIcon.vue";
import GreenDinosaur from "./icons/GreenDinosaur.vue";
export default {
  components: {
    GreenDinosaur,
    ArrowDownIconVue,
  },
  name: "HeaderLorem",
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat");

.header-position {
  background-color: #000000;
  display: flex;
  align-items: center;
  height: 150px;
  margin: -8px -8px 0px -8px;
  padding-left: 173px;
}
.common-style {
  font-family: "Montserrat";
  font-style: italic;
  display: flex;
  align-items: center;
  font-weight: 700;
  padding-left: 9px;
  font-size: 24px;
  line-height: 29px;
  text-transform: uppercase;
  text-shadow: 0px 4px 30px #21612f;
}
.title {
  color: #ffffff;
}
.second-title {
  color: #d9ef0c;
  padding-right: 107px;
}
.sub-title {
  display: flex;
  align-items: center;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 22px;
  padding-right: 30px;
  color: #ffffff;
}
.arrow-down{
  margin-left: 4px;
}

</style>
