<template>
<MainBody/>
<Catalog/>
<FeaturedProducts/>
<TopBought/>
<ProductsYouMightLike/>
<BestIdeas/>
</template>

<script>

import Catalog from './bodyContents/Catalog.vue'
import FeaturedProducts from './bodyContents/FeaturedProducts.vue'
import TopBought from './bodyContents/TopBought.vue'
import ProductsYouMightLike from './bodyContents/ProductsYouMightLike.vue'
import BestIdeas from './bodyContents/BestIdeas.vue'
import MainBody from './bodyContents/MainBody.vue'

export default {
  name: "BodyContents",
  components:{
    Catalog,
    FeaturedProducts,
    TopBought,
    ProductsYouMightLike,
    BestIdeas,
    MainBody,
  }
};
</script>

<style scoped>
  @import url('https://fonts.cdnfonts.com/css/montserrat');
.header-container {
  width: 100%;
  background-color: #000000;
  font-family: "Montserrat", sans-serif;
  color: #ffffff;
  display: flex;
  justify-content: space-between;
  overflow: hidden;
  margin: auto;
  padding: 2px;
  
}
.menu{
padding:5px;
}
.login-icon{
    display: flex;
    justify-content: space-between;
    padding:30px;
}

</style>
