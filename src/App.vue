<!-- JavaScript -->
<script>
import AppHeader from "./components/AppHeader.vue"; //importo "AppHeader"
import AppMain from "./components/AppMain.vue"; //importo "AppMain"

//Esporto
export default {
  //Componenti
  components: {
    AppHeader, //AppHeader
    AppMain, //AppMain
  }
}

</script>

<!-- Template -->
<template>
  <!-- Header -->
  <AppHeader></AppHeader>
  <!-- Main -->
  <AppMain></AppMain>
</template>

<!-- CSS -->
<style scoped>
</style>