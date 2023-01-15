<template>
  <div class="products-container">
    <div class='mini-container'>
      <h1>Products you might like</h1>
      <div>
        <FeaturedProduct
          :key="product.id"
          v-for="product in products"
          :product="product"
        />
      </div>
    </div>
  </div>
</template>

<script>
import FeaturedProduct from "./FeaturedProduct.vue";
export default {
  name: "FeaturedProducts",
  components: {
    FeaturedProduct,
  },
  data: () => ({
    products: [
      {
        title: "Lorem ipsum dolor sit",
        id: 1,
        price: 12,
        imageUrl: require("../../assets/images/featured-products/image1.jpeg"),
        logo: require("../../assets/logos/brignoli-grey.svg"),
      },
      {
        title: "Lorem ipsum dolor sit",
        id: 2,
        price: 12,
        imageUrl: require("../../assets/images/featured-products/image2.jpeg"),
        logo: require("../../assets/logos/brignoli-grey.svg"),
      },
      {
        title: "Lorem ipsum dolor sit",
        id: 3,
        price: 12,
        imageUrl: require("../../assets/images/featured-products/image3.jpeg"),
        logo: require("../../assets/logos/brignoli-grey.svg"),
      },
      {
        title: "Lorem ipsum dolor sit",
        id: 4,
        price: 12,
        imageUrl: require("../../assets/images/featured-products/image4.jpeg"),
        logo: require("../../assets/logos/brignoli-grey.svg"),
      },
    ],
  }),
};
</script>

<style scoped>
.products-container {
  background-color: #edeae6;
  padding-top: 1%;
  padding-bottom: 3%;
  margin-top: 2%;
  margin-bottom: 5px;
  width: 100%;
}
h1 {
  font-family: bodoni moda;
  font-weight: 700;
  line-height: 67px;
  font-size: 50px;

}
.mini-container{
  margin: 60px;
}
</style>
