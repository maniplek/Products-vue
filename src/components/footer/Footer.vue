<template>

</template>

<script>
import Clients from "./Clients.vue";
import Service from "./Service.vue";
export default {
  name: "Footer",
  components: {
    Clients,
    Service,
  },
  data: () => ({
    services: [
      {
        title: "SETTORI",
        contents: ["Filati", "Tessuti", "Nobilitazione", "Editoria"],
      },
      {
        title: "INNOVAZIONE",
        contents: [
          "CreativitÃ  e Design",
          "RealtÃ  produttiva",
          "Vision Digitale",
        ],
      },
      {
        title: "ResponsabilitÃ ",
        contents: ["Economica", "Ambientale", "Sociale"],
      },
      {
        title: "CARRIERA",
        contents: ["Giovani", "Scuola lavoro", "Lavora con noi"],
      },
    ],
  }),
};
</script>

<style scoped>
.container {
  margin-top: 10px;
  background-color: #1e1e1e;
}
</style>
