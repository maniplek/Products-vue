<template>
  <div class="container">
    <h4 class="title service-element">{{service.title.toUpperCase()}}</h4>
    <div class="service-element" :key="element" v-for="element in service.contents">{{element}}</div>
  </div>
</template>

<script>
export default {
  name: "Services",
  props: {
    service: Object
  }
}
</script>