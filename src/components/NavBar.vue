<template>
  <div class="nav-container">
    <div class="">
      <img src="../assets/logos/brignoli.svg" alt=" " />
    </div>

    <div class="menu">
      <p>CATALOG</p>
      <p>
        "SOLUTIONS", "NEWS", "PROJECTS", "ABOUT", "PRESS", "CONTACT",
        "TEXTURES", "INSPIRATION"
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {
      items: [
        "SOLUTIONS",
        "NEWS",
        "PROJECTS",
        "ABOUT",
        "PRESS",
        "CONTACT",
        "TEXTURES",
        "INSPIRATION",
      ],
    };
  },
};
</script>

<style scoped>
@import url("https://fonts.cdnfonts.com/css/montserrat");
.nav-container {
  width: 100%;
  background-color: #a3846b;
  font-family: "Montserrat", sans-serif;
  color: #ffffff;
  display: flex;
  justify-content: space-between;
  overflow: hidden;
  margin: auto;
  padding: 2px;
}
.menu {
  padding: 10px;
  display: flex;
  justify-content: space-between;
}
</style>
