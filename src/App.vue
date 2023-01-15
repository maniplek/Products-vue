<template>
<Header />
<NavBar />
<BodyContents/>
<Footer/>
</template>

<script>
import Header from '@/components/Header.vue'
import NavBar from '@/components/NavBar.vue'
import BodyContents from '@/components/BodyContents.vue'
import Footer from '@/components/footer/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    NavBar,
    BodyContents,
    Footer,
  }
}
</script>

<style>
* {
    margin: 0;
    padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;


}
</style>
