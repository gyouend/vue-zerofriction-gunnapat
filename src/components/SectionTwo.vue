<template>
  <div class="bg-section-two">
    <span class="lorem-title title">LOREM IPSUM</span>
    <span class="lorem-title second-title">LOREM</span>
    <div>
      <img class="image-size" src="../assets/TwoPeople.png" />
    </div>
    <div class="main-detail">
      <span>Lorem Ipsum is simply</span>
    </div>
    <div class="sub-detail">
      <span
        >Lorem Ipsum is simply dummy text of the printing and typesetting
        industry. Lorem Ipsum has been the industry's standard dummy text ever
        since the 1500s, when an unknown printer took a galley of type and
        scrambled it to make a type specimen book.</span
      >
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionTwo",
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat");

.bg-section-two {
  background-color: #000000;
  height: 900px;
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
  padding: 104px 15px 0px 600px;
  color: #ffffff;
}
.second-title {
  color: #d9ef0c;
}
.image-size {
  padding: 104px 0px 0px 860px;
  width: 200px;
  height: 200px;
}

.main-detail {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 600;
  font-size: 26px;
  line-height: 32px;
  padding-left: 809px;
  padding-top: 61px;
  color: #FFFFFF;
}

.sub-detail {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 600;
  font-size: 26px;
  line-height: 32px;
  width: 1300px;
  padding: 20px 0px 0px 420px;
  color: #FFFFFF;
  text-align: center;
}
</style>
