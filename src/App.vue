<!-- JavaScript -->
<script>
import AppHeader from "./components/AppHeader.vue"; //importo "AppHeader"
import AppMain from "./components/AppMain.vue"; //importo "AppMain"
import AppFooter from "./components/AppFooter.vue"; //importo "AppFooter"

//Esporto
export default {
  //Componenti
  components: {
    AppHeader, //AppHeader
    AppMain, //AppMain
    AppFooter //AppFooter
  }
}
</script>

<!-- Template -->
<template>
  <!-- Header -->
  <AppHeader></AppHeader>
  <!-- Main -->
  <AppMain></AppMain>
  <!-- Footer -->
  <AppFooter></AppFooter>
</template>

<!-- CSS -->
<style scoped>
</style>