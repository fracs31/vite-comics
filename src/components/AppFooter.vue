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
</style>