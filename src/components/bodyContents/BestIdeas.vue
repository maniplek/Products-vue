<template>
  <div class="container">
    <div>
      <img src="../../assets/images/best-ideas-sofa.jpeg" />
    </div>
    <div class="second-container">
      <h1>The best ideal for sofas </h1>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias sequi
        alias iusto dicta odit ea atque quibusdam, ipsam quidem mollitia
        perferendis. Perspiciatis, quasi mollitia. Corrupti at ratione
        cupiditate mollitia voluptate?
      </p>

      <button class="btn">Show more </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "BestIdeas",
};
</script>

<style scoped>
.container {
  color: white;
  display: flex;
  justify-content: space-between;
  gap:10px;
}

.second-container{
  background-color: #1E1E1E;
  padding: 15px;
}
h1 {
  font-family: bodoni moda;
  font-weight: 700;
  line-height: 67px;
  font-size: 50px;
  margin-bottom: 80px;
}

.btn{
  margin-top: 40px;
  border-radius: 18px;
  border: 2px solid rgb(167, 167, 167); /* Green */
  padding: 12px;
  width: 200px;
  background-color: #1E1E1E;
  color: white;
  
}

</style>
