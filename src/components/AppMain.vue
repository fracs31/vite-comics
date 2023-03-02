<!-- JavaScript -->
<script>
import Content from "./Content.vue"; //importo "Content.vue"
import Discover from "./Discover.vue"; //importo "Discover.vue"

//Esporto
export default {
    //Componenti
    components: {
        Content, //contenuto
        Discover, //discover
    }
}

</script>

<!-- Template -->
<template>
    <!-- Main -->
    <main class="main-content">
        <!-- Contenuto -->
        <Content></Content>
        <!-- Discover -->
        <Discover></Discover>
    </main>
</template>

<!-- CSS -->
<style scoped>
    
</style>