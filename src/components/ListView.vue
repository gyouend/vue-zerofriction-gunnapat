<template>
  <div class="area-card" v-for="(product, index) in products" :key="index">
    <div> 
        <img class="image-size" :src="product.thumbnail" />
    </div>
    <div class="main-detail"> 
        <span>{{ product.title }}</span>
    </div>
    <div class="sub-detail"> 
        <span>{{ product.description }}</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "ListView",
  data() {
    return {
      products: [],
    };
  },
  async mounted() {
    try {
      //get api title,description,imageUrl use when product.value krub
      //basiclly way (not axios lib)
      const response = await fetch('https://dummyjson.com/products?limit=3');
      const data = await response.json();
      this.products = data.products;
    } catch (error) {
      console.log(error);
    }
  },
};
</script>

<style scoped>
.area-card {
  background: #ffffff;
  height: 443px;
  width: 416px;
  margin-left: 24px;
  margin-top: 64px;
  box-shadow: 0px 4px 25px rgba(0, 0, 0, 0.06);
  border-radius: 4px;
}

.image-size {
  width: 416px;
  height: 236px;
}
.main-detail {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 600;
  font-size: 26px;
  line-height: 32px;
  color: #000000;
  height: 45px;
  padding: 33px 22px 0px 25px;
}

.sub-detail {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 130%;
  color: #333333;
  width: 369px;
  padding: 0px 22px 70px 25px;
}
</style>
