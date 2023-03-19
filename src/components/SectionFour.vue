<template>
  <div class="bg-section-four">
    <div>
      <img class="image-size" src="../assets/MotorBic.png" />
    </div>
    <div class="form-position">
      <span class="title">ติดต่อเรา</span>
      <div>
        <input class="area-input" placeholder="ชื่อ - นามสกุล" />
      </div>
      <div>
        <input class="area-input" placeholder="เบอร์ติดต่อ" />
      </div>
      <div>
        <input class="area-input" placeholder="อีเมล" />
      </div>
      <div>
        <input class="area-input" placeholder="วันที่" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionFour",
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat");
@import url("https://fonts.googleapis.com/css2?family=Noto+Sans+Thai");

.bg-section-four {
  display: flex;
  background-color: #000000;
  height: 1000px;
  margin: 0px -8px 0px -8px;
}
.image-size {
  padding: 260px 141px 320px 229px;
  width: 719px;
  height: 423px;
}
.form-position {
  padding-top: 201px;
}

.title {
  font-family: "Noto Sans Thai";
  font-weight: 600;
  font-size: 60px;
  line-height: 73px;
  text-transform: capitalize;
  color: #ffffff;
}

input::placeholder {
  font-family: "Noto Sans Thai";
  font-weight: 400;
  font-size: 18px;
  line-height: 22px;
}
input {
  background-color: #000000;
  border: none;
  border-bottom: 2px solid #f5f5f5;
  color: #f5f5f5;
}

.area-input {
  width: 519px;
  height: 36px;
  padding-top: 37px;
}
</style>
