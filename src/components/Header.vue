<template>
  <div class="header-container">
    <div class="">
      <img src="../assets/logos/martineli-logo.svg" alt=" " />
    </div>

    <div class="login-icon">
    <img class="icon" src="../assets/icons/person.icon.svg"/>
      <h3>LOG IN</h3>
    </div>

    <div class='menu'>

      <img src="../assets/icons/menu-toggle.svg" alt="" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
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
