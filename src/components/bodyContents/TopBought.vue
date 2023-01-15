<template>
  <div class="container">
    <div class="content">
      <h1>Top Bougth products</h1>
      <p
        >Lorem ipsum dolor sit amet, consectetur adipisicing elit. Asperiores,
        nisi. Eius, distinctio quis dicta eveniet molestiae magni voluptas,
        libero laboriosam quam consequatur vero incidunt odio delectus.
        Temporibus dignissimos facere doloremque.</p
      >
      <p
        >Lorem ipsum dolor sit amet, consectetur adipisicing elit. Asperiores,
        nisi. Eius, distinctio quis dicta eveniet molestiae magni voluptas,
        libero laboriosam quam consequatur vero incidunt odio delectus.
        Temporibus dignissimos facere doloremque.</p
      >
      <p
        >Lorem ipsum dolor sit amet, consectetur adipisicing elit. Asperiores,
        nisi. Eius, distinctio quis dicta eveniet molestiae magni voluptas,
        libero laboriosam quam consequatur vero incidunt odio delectus.
        Temporibus dignissimos facere doloremque.</p
      >
    </div>
    <div>
    <img src="../../assets/images/liked-products/image1.jpeg"/>
    </div>
  </div>
</template>

<script>
export default {
  name: "TopBought",
};
</script>

<style scoped>
h1 {
  font-family: bodoni moda;
  font-weight: 700;
  line-height: 67px;
  font-size: 50px;
}
.container {
  margin: 60px;
  display: flex;
  justify-content: space-between;
}
span{
text-align: center;
}
.content p{
  align-items: center;
  align-items: center;
  padding-bottom: 10px;
  padding-top: 10px;
}

  .content {
    flex-basis: 40%;
    margin: auto;
  }
</style>
