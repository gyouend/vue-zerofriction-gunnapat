<template>
  <div class="bg-section-three">
    <div class="lorem-title title">
      <span>LOREM IPSUM</span>
    </div>
    <v-row class="reverse-position">
      <v-col class="space-items">
        <ListView />
      </v-col>
      <v-col class="space-items">
        <ListView />
      </v-col>
      <v-col class="space-items">
        <ListView />
      </v-col>
    </v-row>
  </div>
</template>

<script>
import ListView from "./ListView.vue";
export default {
  name: "SectionThree",
  components: {
    ListView,
  },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat");

.bg-section-three{
  background: #d9ef0c;
  height: 1000px;
  margin: 0px -8px 0px -8px;
}
.lorem-title {
  width: 600px;
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 700;
  font-size: 60px;
  line-height: 73px;
  text-transform: uppercase;
}

.title {
  padding-top: 128px;
  padding-left: 728px;
  color: #000000;
}

.reverse-position {
  display: flex;
  flex-direction: row;
  padding-left: 312px;
}

.space-items{
    padding-right: 24px;
}
</style>
