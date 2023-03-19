<template>
  <div class="bg-section-four">
    <div>
      <img class="image-size" src="../assets/MotorBic.png" />
    </div>
    <div class="form-position">
      <form>
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
        <div class="datepicker-wrapper">
          <VueDatePicker
            placeholder="วันที่"
            class="custom-datepicker"
            v-model="date"
          >
          </VueDatePicker>
        </div>
        <div class="text-position">
          <div class="detail">
            <span>Lorem Ipsum is simply dummy text</span>
          </div>
          <div class="detail">
            <span>Lorem Ipsum is simply dummy text</span>
          </div>
        </div>
        <button class="loren-button">LOREM</button>
      </form>
    </div>
  </div>
</template>

<script>
import VueDatePicker from "@vuepic/vue-datepicker";
import "@vuepic/vue-datepicker/dist/main.css";
import { ref } from "vue";
export default {
  name: "SectionFour",
  setup() {
    const picked = ref(new Date());
    return { picked };
  },
  components: {
    VueDatePicker,
  },
  data() {
    return {
      date: null,
    };
  },
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
  margin-top: 37px;
}

.custom-datepicker::v-deep input {
  background-color: #000000;
  display: flex;
  width: 519px;
  height: 36px;
  margin-top: 37px;
  border: none;
  border-bottom: 2px solid #f5f5f5;
  color: #f5f5f5;
  z-index: 1;
}

.custom-datepicker::v-deep input::placeholder {
  color: #f5f5f5;
}

.detail {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 140.9%;
  color: #ffffff;
}

.text-position {
  padding-top: 34px;
}

.loren-button {
  height: 56px;
  width: 290px;
  margin-top: 75px;
  background: linear-gradient(180deg, #dee34b 0%, #d9ef0c 35.94%, #87a30d 100%);
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.35);
  border-radius: 50px;
  border-width: 0px;
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 18px;
  color: #000000;
  letter-spacing: 0.1px;
}

</style>
