<!-- JavaScript -->
<script>
</script>

<!-- Template -->
<template>
    <!-- Header -->
    <header class="main-header">
        <!-- Container -->
        <div class="container">
            <!-- Navbar -->
            <nav class="navbar">
                <!-- Logo -->
                <div class="navbar__logo">
                    <!-- Immagine -->
                    <img class="navbar__logo--img" src="../assets/img/dc-logo.png" alt="Logo">
                </div>
                <!-- Lista -->
                <ul class="navbar__list">
                    <!-- Elemento della lista -->
                    <li class="navbar__list-item">Characters</li>
                    <!-- Elemento della lista -->
                    <li class="navbar__list-item active">Comics</li>
                    <!-- Elemento della lista -->
                    <li class="navbar__list-item">Movies</li>
                    <!-- Elemento della lista -->
                    <li class="navbar__list-item">Tv</li>
                    <!-- Elemento della lista -->
                    <li class="navbar__list-item">Games</li>
                    <!-- Elemento della lista -->
                    <li class="navbar__list-item">Collectibles</li>
                    <!-- Elemento della lista -->
                    <li class="navbar__list-item">Videos</li>
                    <!-- Elemento della lista -->
                    <li class="navbar__list-item">Fans</li>
                    <!-- Elemento della lista -->
                    <li class="navbar__list-item">News</li>
                    <!-- Elemento della lista -->
                    <li class="navbar__list-item">Shop</li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<!-- CSS -->
<style scoped>
    /* Header */
    .main-header {
        background-color: white;
        padding: 20px 0px;
    }
    /* Navbar */
    .navbar {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    /* Immagine usata come logo */
    .navbar__logo--img {
        width: 80px;
        aspect-ratio: 1/1;
        object-fit: contain;
    }
    /* Lista della Navbar */
    .navbar__list {
        display: flex;
        align-items: center;
        gap: 30px;
    }
    /* Elementi della lista della Navbar */
    .navbar__list-item {
        text-transform: uppercase;
        color: var(--grey);
        font-size: 14px;
        padding: 40px 0px;
    }
    /* Elemento della lista della Navbar attivo */
    .navbar__list-item.active {
        color: var(--blue);
        position: relative;
    }
    /* Barra dell'elemento della lista della Navbar attivo */
    .navbar__list-item.active::after {
        content: "";
        display: block;
        height: 3px;
        width: 100%;
        background-color: var(--blue);
        position: absolute;
        left: 0px;
        bottom: -20px;
    }
</style>