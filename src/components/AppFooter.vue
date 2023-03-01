<!-- JavaScript -->
<script>
</script>

<!-- Template -->
<template>
    <!-- Footer -->
    <footer class="page-footer">
        <!-- Container -->
        <div class="container">
            <!-- Footer Top -->
            <div class="footer-top">
                <!-- Informazioni -->
                <div class="infos">
                    <!-- Box informazione -->
                    <div class="box-info">
                        <!-- Sottotitolo -->
                        <h3 class="box-info__title">Dc Comics</h3>
                        <!-- Lista -->
                        <ul class="box-info__list">
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Characters</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Comics</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Movies</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">TV</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Games</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Videos</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">News</li>
                        </ul>
                    </div>
                    <!-- Box informazione -->
                    <div class="box-info">
                        <!-- Sottotitolo -->
                        <h3 class="box-info__title">DC</h3>
                        <!-- Lista -->
                        <ul class="box-info__list">
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Terms Of Use</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Privacy policy (New)</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Ad Choices</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Advertising</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Jobs</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Subscriptions</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Talent Workshops</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">CPSC Certificates</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Rating</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Shop Help</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Contact Us</li>
                        </ul>
                    </div>
                    <!-- Box informazione -->
                    <div class="box-info">
                        <!-- Sottotitolo -->
                        <h3 class="box-info__title">Sites</h3>
                        <!-- Lista -->
                        <ul class="box-info__list">
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">DC</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">MAD Magazine</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">DC Kids</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">DC Universe</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">DC Power Visa</li>
                        </ul>
                    </div>
                    <!-- Box informazione -->
                    <div class="box-info">
                        <!-- Sottotitolo -->
                        <h3 class="box-info__title">Shop</h3>
                        <!-- Lista -->
                        <ul class="box-info__list">
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Shop DC</li>
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item">Shop DC Collectibles</li>
                        </ul>
                    </div>
                </div>
                <!-- Logo grande -->
                <div class="big-logo">
                    <!-- Immagine -->
                    <img class="big-logo__img" src="../assets/img/dc-logo-bg.png" alt="Big Logo">
                </div>
            </div>
        </div>
        <!-- Footer Bottom -->
        <div class="footer-bottom">
            <!-- Container -->
            <div class="container">
                <!-- Sottoiscrizione -->
                <div class="subscription">
                    <!-- Bottone -->
                    <button class="sign-up">
                        Sign-up now!
                    </button>
                    <!-- Seguici -->
                    <div class="follow-us">
                        <!-- Sottotitolo -->
                        <h4 class="follow-us__title">Follow Us</h4>
                        <!-- Lista -->
                        <ul class="follow-us__list">
                            <!-- Elemento della lista -->
                            <li class="follow-us__list-item">
                                <!-- Immagine -->
                                <img class="follow-us__list-item--img" src="../assets/img/footer-facebook.png" alt="Facebook">
                            </li>
                            <!-- Elemento della lista -->
                            <li class="follow-us__list-item">
                                <!-- Immagine -->
                                <img class="follow-us__list-item--img" src="../assets/img/footer-twitter.png" alt="Twitter">
                            </li>
                            <!-- Elemento della lista -->
                            <li class="follow-us__list-item">
                                <!-- Immagine -->
                                <img class="follow-us__list-item--img" src="../assets/img/footer-youtube.png" alt="YouTube">
                            </li>
                            <!-- Elemento della lista -->
                            <li class="follow-us__list-item">
                                <!-- Immagine -->
                                <img class="follow-us__list-item--img" src="../assets/img/footer-pinterest.png" alt="Pinterest">
                            </li>
                            <!-- Elemento della lista -->
                            <li class="follow-us__list-item">
                                <!-- Immagine -->
                                <img class="follow-us__list-item--img" src="../assets/img/footer-periscope.png" alt="Periscope">
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<!-- CSS -->
<style scoped>
    /* Footer */
    .page-footer {
        background-image: url("../assets/img/footer-bg.jpg");
    }
    /* Footer Top */
    .footer-top {
        display: flex;
        justify-content: space-between;
    }
    /* Informazioni */
    .infos {
        padding: 35px 0px;
        width: 400px;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
    }
    /* Titolo del box informazioni */
    .box-info__title {
        color: white;
        text-transform: uppercase;
        margin-bottom: 10px;
    }
    /* Elemento della lista del box informazioni */
    .box-info__list-item {
        color: var(--light-grey);
        font-size: 14px;
        margin-bottom: 5px;
    }
    /* Logo grande */
    .big-logo {
        position: relative;
    }
    /* Immagine del logo grande */
    .big-logo__img {
        width: 550px;
        aspect-ratio: 1/1;
        position: absolute;
        right: 0px;
        top: -50px;
    }
    /* Footer Bottom */
    .footer-bottom {
        background-color: var(--dark-grey);
        padding: 30px 0px;
        position: relative;
        z-index: 1;
    }
    /* Sottoiscrizione */
    .subscription {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    /* Bottone */
    .sign-up {
        font-size: 18px;
        color: white;
        text-transform: uppercase;
        background-color: transparent;
        border: 1px solid var(--blue);
        padding: 15px 10px;
    }
    /* Seguici */
    .follow-us {
        display: flex;
        align-items: center;
        gap: 25px;
    }
    /* Titolo di Seguici */
    .follow-us__title {
        color: var(--blue);
        font-size: 18px;
        text-transform: uppercase;
    }
    /* Lista dei social */
    .follow-us__list {
        display: flex;
        gap: 15px;
    }
    /* Immagine dell'elemento della lista dei social */
    .follow-us__list-item--img {
        width: 35px;
        aspect-ratio: 1/1;
        object-fit: contain;
    }
</style>