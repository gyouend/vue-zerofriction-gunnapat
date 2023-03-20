<template>
  <!-- I didn't use grid layout because I followed figma padding/margin  -->
  <div class="bg-section-one">
    <div class="space-title">
      <div><span class="lorem-title title">LOREM</span></div>
      <span class="lorem-title second-title">IPSUM</span>
      <div><img class="image-size" src="../../assets/MotorBic.png" /></div>
    </div>
    <div class="main-detail">
      <span
        >Lorem Ipsum is simply Lorem Ipsum is simply Lorem Ipsum is simply</span
      >
    </div>
    <div class="sub-detail">
      <span
        >Lorem Ipsum is simply dummy text of the printing and typesetting
        industry. Lorem Ipsum has been the industry's
      </span>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionOne",
  components: {},
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat");
.bg-section-one {
  background-color: #000000;
  height: 868px;
  margin: 0px -8px 0px -8px;
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
  padding-left: 312px;
  padding-top: 69px;
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
  padding-left: 312px;
  padding-top: 15px;
}

.image-size {
  width: 858px;
  height: 505px;
  padding-left: 505px;
  margin-top: -234px;
  padding-right: 245px;
}
</style>
