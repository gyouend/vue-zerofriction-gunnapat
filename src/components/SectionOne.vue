<template>
  <div class="bg-section-one">
    <v-row>
      <v-col class="left-container" cols="6">
        <v-row class="lorem-title title">
          <span>LOREM</span>
        </v-row>
        <v-row class="lorem-title second-title">
          <span>IPSUM</span>
        </v-row>
        <v-row class="main-detail">
          <span
            >Lorem Ipsum is simply Lorem Ipsum is simply Lorem Ipsum is
            simply</span
          >
        </v-row>
        <v-row class="sub-detail">
          <span
            >Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's
          </span>
        </v-row>
      </v-col>
      <v-col class="right-container" cols="6">
        <v-img class="image-size" src="../assets/MotorBic.png" />
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: "SectionOne",
  components: {},
};
</script>
<style scoped>
.bg-section-one {
  background-color: #000000;
  height: 868px;
}

.space-title {
  padding: 178px 0px 0px 312px;
  height: 234px;
}

.lorem-title {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 700;
  font-size: 96px;
  line-height: 117px;
  text-transform: uppercase;
  text-shadow: 0px 4px 30px #21612f;
}

.title {
  color: #ffffff;
}
.second-title {
  color: #d9ef0c;
}

.main-detail {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
  line-height: 24px;
  width: 440px;
  height: 52px;
  color: #ffffff;
}

.sub-detail {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 150%;
  width: 440px;
  height: 80px;
  color: #ffffff;
}

.image-size {
  width: 858px;
  height: 504px;
}

.left-container{
 padding-top: 178px;
 padding-left: 400px;
}
.right-container{
  padding-top: 178px;
}
</style>
