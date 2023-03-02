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
            <!-- Serie -->
            <div class="current-series">
                <!-- Container -->
                <div class="container">
                    <!-- Titolo -->
                    <h2 class="current-series__title">
                        Current Series
                    </h2>
                    <!-- Lista -->
                    <ul class="current-series__list">
                        <!-- Elemento della lista -->
                        <li class="current-series__list-item">
                            <!-- Carta -->
                            <div class="card">
                                <!-- Immagine della carta-->
                                <div class="card__img">
                                    <!-- Immagine -->
                                    <img class="card__img--img" src="../assets/img/prova.jpg" alt="">
                                </div>
                                <!-- Titolo della carta -->
                                <div class="card__title">
                                    <!-- Titolo -->
                                    <h3 class="card__title--title">
                                        Action Comics
                                    </h3>
                                </div>
                            </div>
                        </li>
                        <!-- Elemento della lista -->
                        <li class="current-series__list-item">
                            <!-- Carta -->
                            <div class="card">
                                <!-- Immagine della carta-->
                                <div class="card__img">
                                    <!-- Immagine -->
                                    <img class="card__img--img" src="../assets/img/prova.jpg" alt="">
                                </div>
                                <!-- Titolo della carta -->
                                <div class="card__title">
                                    <!-- Titolo -->
                                    <h3 class="card__title--title">
                                        Action Comics
                                    </h3>
                                </div>
                            </div>
                        </li>
                        <!-- Elemento della lista -->
                        <li class="current-series__list-item">
                            <!-- Carta -->
                            <div class="card">
                                <!-- Immagine della carta-->
                                <div class="card__img">
                                    <!-- Immagine -->
                                    <img class="card__img--img" src="../assets/img/prova.jpg" alt="">
                                </div>
                                <!-- Titolo della carta -->
                                <div class="card__title">
                                    <!-- Titolo -->
                                    <h3 class="card__title--title">
                                        Action Comics
                                    </h3>
                                </div>
                            </div>
                        </li>
                        <!-- Elemento della lista -->
                        <li class="current-series__list-item">
                            <!-- Carta -->
                            <div class="card">
                                <!-- Immagine della carta-->
                                <div class="card__img">
                                    <!-- Immagine -->
                                    <img class="card__img--img" src="../assets/img/prova.jpg" alt="">
                                </div>
                                <!-- Titolo della carta -->
                                <div class="card__title">
                                    <!-- Titolo -->
                                    <h3 class="card__title--title">
                                        Action Comics
                                    </h3>
                                </div>
                            </div>
                        </li>
                        <!-- Elemento della lista -->
                        <li class="current-series__list-item">
                            <!-- Carta -->
                            <div class="card">
                                <!-- Immagine della carta-->
                                <div class="card__img">
                                    <!-- Immagine -->
                                    <img class="card__img--img" src="../assets/img/prova.jpg" alt="">
                                </div>
                                <!-- Titolo della carta -->
                                <div class="card__title">
                                    <!-- Titolo -->
                                    <h3 class="card__title--title">
                                        Action Comics
                                    </h3>
                                </div>
                            </div>
                        </li>
                        <!-- Elemento della lista -->
                        <li class="current-series__list-item">
                            <!-- Carta -->
                            <div class="card">
                                <!-- Immagine della carta-->
                                <div class="card__img">
                                    <!-- Immagine -->
                                    <img class="card__img--img" src="../assets/img/prova.jpg" alt="">
                                </div>
                                <!-- Titolo della carta -->
                                <div class="card__title">
                                    <!-- Titolo -->
                                    <h3 class="card__title--title">
                                        Action Comics
                                    </h3>
                                </div>
                            </div>
                        </li>
                        <!-- Elemento della lista -->
                        <li class="current-series__list-item">
                            <!-- Carta -->
                            <div class="card">
                                <!-- Immagine della carta-->
                                <div class="card__img">
                                    <!-- Immagine -->
                                    <img class="card__img--img" src="../assets/img/prova.jpg" alt="">
                                </div>
                                <!-- Titolo della carta -->
                                <div class="card__title">
                                    <!-- Titolo -->
                                    <h3 class="card__title--title">
                                        Action Comics
                                    </h3>
                                </div>
                            </div>
                        </li>
                    </ul>
                </div>
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
    /* Titolo di Current Series */
    .current-series__title {
        font-size: 20px;
        text-transform: uppercase;
        background-color: var(--blue);
        max-width: fit-content;
        padding: 15px 10px;
        position: relative;
        top: -25px;
        z-index: 1;
    }
    /* Lista delle serie */
    .current-series__list {
        padding-bottom: 50px;
        display: flex;
        flex-wrap: wrap;
        gap: 50px 25px;
    }
    /* Immagine della carta */
    .card__img {
        margin-bottom: 15px;
    }
    /* Immagine usata della carta */
    .card__img--img {
        width: 185px;
        aspect-ratio: 1/1;
        object-fit: cover;
        object-position: top;
    }
    /* Titolo usato della carta */
    .card__title--title {
        text-transform: uppercase;
        font-weight: normal;
        font-size: 16px;
    }
</style>