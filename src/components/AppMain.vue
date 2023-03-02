<!-- JavaScript -->
<script>
import Discover from "./Discover.vue"; //importo "Discover.vue"

//Esporto
export default {
    //Componenti
    components: {
        Discover, //Discover
    }
}

</script>

<!-- Template -->
<template>
    <!-- Main -->
    <main class="main-content">
        <!-- Contenuto -->
        <div class="content">
            <!-- Jumbotron -->
            <div class="jumbotron">
                <!-- Immagine -->
                <img class="jumbotron__img" src="../assets/img/jumbotron.jpg" alt="Jumbotron">
            </div>
            <!-- Container -->
            <div class="container">
            </div>
        </div>
        <!-- Discover -->
        <Discover></Discover>
    </main>
</template>

<!-- CSS -->
<style scoped>
    /* Contenuto */
    .content {
        background-color: var(--black);
        color: white;
    }
    /* Jumbotron */
    .jumbotron {
        height: 400px;
        width: 100%;
    }
    /* Immagine del Jumbotron */
    .jumbotron__img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        object-position: top;
    }
</style>