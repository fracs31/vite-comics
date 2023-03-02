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
            <!-- Container -->
            <div class="container">
                <!-- Titolo -->
                <h1>-- Content goes here --</h1>
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
        padding: 45px 0px;
        color: white;
    }
</style>