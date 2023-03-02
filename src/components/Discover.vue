<!-- JavaScript -->
<script>

//Esporto
export default {
    data() {
        return {
            //Elementi della lista di Discover
            discoverListItems: [
                {
                    img: "../src/assets/img/buy-comics-digital-comics.png", //immagine
                    description: "Digital Comics", //descrizione
                },
                {
                    img: "../src/assets/img/buy-comics-merchandise.png", //immagine
                    description: "DC Merchandise", //descrizione
                },
                {
                    img: "../src/assets/img/buy-comics-subscriptions.png", //immagine
                    description: "Subscription", //descrizione
                },
                {
                    img: "../src/assets/img/buy-comics-shop-locator.png", //immagine
                    description: "Comic Shop Locator", //descrizione
                },
                {
                    img: "../src/assets/img/buy-dc-power-visa.svg", //immagine
                    description: "DC Power Visa", //descrizione
                },
            ]
        }
    }
};

</script>

<!-- Template -->
<template>
    <!-- Discover -->
    <div class="discover">
        <!-- Container -->
        <div class="container">
            <!-- Lista -->
            <ul class="discover__list">
                <!-- Elemento della lista -->
                <li class="discover__list-item" v-for="(item) in discoverListItems">
                    <!-- Immagine -->
                    <div class="discover__list-item--img">
                        <!-- Immagine -->
                        <img class="discover__list-item--img__img" v-bind:src="item.img" v-bind:alt="item.description">
                    </div>
                    <!-- Descrizione -->
                    <div class="discover__list-item--description">
                        {{ item.description }}
                    </div>
                </li>
            </ul>
        </div>
    </div>
</template>

<!-- CSS -->
<style scoped>
    /* Discover */
    .discover {
        background-color: var(--blue);
        padding: 45px 0px;
        position: relative;
        z-index: 1;
    }
    /* Lista di Discover */
    .discover__list {
        display: flex;
        justify-content: space-around;
        gap: 50px;
    }
    /* Elemento della lista di Discover */
    .discover__list-item {
        display: flex;
        align-items: center;
        gap: 10px;
    }
    /* Immagine dell'elemento della lista di Discover */
    .discover__list-item--img__img {
        width: 50px;
        aspect-ratio: 1/1;
        object-fit: contain;
    }
    /* Descrizione dell'elemento della lista di Discover */
    .discover__list-item--description {
        text-transform: uppercase;
        color: white;
    }
</style>