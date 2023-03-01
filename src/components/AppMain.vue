<!-- JavaScript -->
<script>
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
        <div class="discover">
            <!-- Container -->
            <div class="container">
                <!-- Lista -->
                <ul class="discover__list">
                    <!-- Elemento della lista -->
                    <li class="discover__list-item">
                        <!-- Immagine -->
                        <div class="discover__list-item--img">
                            <!-- Immagine -->
                            <img class="discover__list-item--img__img" src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics">
                        </div>
                        <!-- Descrizione -->
                        <div class="discover__list-item--description">
                            Digital Comics
                        </div>
                    </li>
                    <!-- Elemento della lista -->
                    <li class="discover__list-item">
                        <!-- Immagine -->
                        <div class="discover__list-item--img">
                            <!-- Immagine -->
                            <img class="discover__list-item--img__img" src="../assets/img/buy-comics-merchandise.png" alt="DC Merchandise">
                        </div>
                        <!-- Descrizione -->
                        <div class="discover__list-item--description">
                            DC Merchandise
                        </div>
                    </li>
                    <!-- Elemento della lista -->
                    <li class="discover__list-item">
                        <!-- Immagine -->
                        <div class="discover__list-item--img">
                            <!-- Immagine -->
                            <img class="discover__list-item--img__img" src="../assets/img/buy-comics-subscriptions.png" alt="Subscription">
                        </div>
                        <!-- Descrizione -->
                        <div class="discover__list-item--description">
                            Subscription
                        </div>
                    </li>
                    <!-- Elemento della lista -->
                    <li class="discover__list-item">
                        <!-- Immagine -->
                        <div class="discover__list-item--img">
                            <!-- Immagine -->
                            <img class="discover__list-item--img__img" src="../assets/img/buy-comics-shop-locator.png" alt="Comic Shop Locator">
                        </div>
                        <!-- Descrizione -->
                        <div class="discover__list-item--description">
                            Comic Shop Locator
                        </div>
                    </li>
                    <!-- Elemento della lista -->
                    <li class="discover__list-item">
                        <!-- Immagine -->
                        <div class="discover__list-item--img">
                            <!-- Immagine -->
                            <img class="discover__list-item--img__img" src="../assets/img/buy-dc-power-visa.svg" alt="DC Power Visa">
                        </div>
                        <!-- Descrizione -->
                        <div class="discover__list-item--description">
                            DC Power Visa
                        </div>
                    </li>
                </ul>
            </div>
        </div>
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
    /* Discover */
    .discover {
        background-color: var(--blue);
        padding: 45px 0px;
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