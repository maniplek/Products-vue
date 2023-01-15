<template>
  <div class="catalog-container">
    <h1>Catalog</h1>
    <div class="first-image">
      <div class="image-container">
        <img
          src="../../assets/images/catalog/image1.jpeg"
          alt="Snow"
          style="width: 100%"
        />
        <div class="highlight">
          <h1>Tessuri</h1>
          <hr />
          <span
            >Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis
            asperiores molestiae incidunt. Voluptatibus ex iure aut delectus
            doloribus unde fuga iste voluptas corporis illum vitae, fugiat
            reprehenderit soluta, facere doloremque?</span
          >
        </div>
      </div>
    </div>
    <div class="min-container">
      <div class="first-image">
        <div class="image-container">
          <img
            src="../../assets/images/catalog/image2.jpeg"
            alt="Snow"
            style="width: 100%"
          />
          <div class="highlight">
            <h1>Tessuri</h1>
            <hr />
            <span
              >Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis
              asperiores molestiae incidunt. Voluptatibus ex iure aut delectus
              doloribus unde fuga iste voluptas corporis illum vitae, fugiat
              reprehenderit soluta, facere doloremque?</span
            >
          </div>
        </div>
      </div>
      <div class="first-image">
        <div class="image-container">
          <img
            src="../../assets/images/catalog/image3.jpeg"
            alt="Snow"
            style="width: 100%"
          />
          <div class="highlight">
            <h1>Tessuri</h1>
            <hr />
            <span
              >Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis
              asperiores molestiae incidunt. Voluptatibus ex iure aut delectus
              doloribus unde fuga iste voluptas corporis illum vitae, fugiat
              reprehenderit soluta, facere doloremque?</span
            >
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Catalog",
};
</script>

<style scoped>
.catalog-container {
  margin: 60px;
}
h1 {
  font-family: bodoni moda;
  font-weight: 700;
  line-height: 67px;
  font-size: 50px;
}
.image-container {
  position: relative;
  text-align: center;
  color: white;
}
hr {
  margin: 10px;
  width: 90px;
  margin-left: auto;
  margin-right: auto;
}
.highlight {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.min-container{
  display: flex;
  flex: 2px;
  justify-content: flex-start;
  gap: 10px;
}
</style>
