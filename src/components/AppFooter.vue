<!-- JavaScript -->
<script>

//Esporto
export default {
    data() {
        return {
            //Info box
            infoBoxes: [
                {
                    title: "Dc Comics", //titolo
                    listItems: ["Characters", "Comics", "Movies", "TV", "Games", "Videos", "News"], //elementi della lista
                },
                {
                    title: "DC", //titolo
                    listItems: ["Terms Of Use", "Privacy policy (New)", "Ad Choices", "Advertising", "Jobs", "Subscriptions", "Talent Workshops", "CPSC Certificates", "Rating", "Shop Help", "Contact Us"], //elementi della lista
                },
                {
                    title: "Sites", //titolo
                    listItems: ["DC", "MAD Magazine", "DC Kids", "DC Universe", "DC Power Visa"], //elementi della lista
                },
                {
                    title: "Shop", //titolo
                    listItems: ["Shop DC", "MAD Shop DC Collectibles"], //elementi della lista
                }
            ],
            //Social
            socials: [
                {
                    fullName: "Facebook", //nome
                    img: "../src/assets/img/footer-facebook.png", //immagine
                },
                {
                    fullName: "Twitter", //nome
                    img: "../src/assets/img/footer-twitter.png", //immagine
                },
                {
                    fullName: "YouTube", //nome
                    img: "../src/assets/img/footer-youtube.png", //immagine
                },
                {
                    fullName: "Pinterest", //nome
                    img: "../src/assets/img/footer-pinterest.png", //immagine
                },
                {
                    fullName: "Periscope", //nome
                    img: "../src/assets/img/footer-periscope.png", //immagine
                },
            ],
        }
    }
};

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
                    <div class="box-info" v-for="(infoBox) in infoBoxes">
                        <!-- Sottotitolo -->
                        <h3 class="box-info__title">{{ infoBox.title }}</h3>
                        <!-- Lista -->
                        <ul class="box-info__list">
                            <!-- Elemento della lista -->
                            <li class="box-info__list-item" v-for="(item) in infoBox.listItems">
                                {{ item }}
                            </li>
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
                            <li class="follow-us__list-item" v-for="(social) in socials">
                                <!-- Immagine -->
                                <img class="follow-us__list-item--img" v-bind:src="social.img" v-bind:alt="social.fullName">
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