<!-- JavaScript -->
<script>

//Esporto
export default {
    //Props
    props: {
        thumb: String, //immagine
        series: String, //nome della serie
    }
}

</script>

<!-- Template -->
<template>
    <!-- Carta -->
    <div class="card">
        <!-- Immagine della carta-->
        <div class="card__img">
            <!-- Immagine -->
            <img class="card__img--img" v-bind:src="thumb" v-bind:alt="series">
        </div>
        <!-- Titolo della carta -->
        <div class="card__title">
            <!-- Titolo -->
            <h3 class="card__title--title">
                {{ series }}
            </h3>
        </div>
    </div>
</template>

<!-- CSS -->
<style scoped>
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