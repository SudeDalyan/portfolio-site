<template>
    <header class="header">
        <img src="../assets/logo.png" class="navbar-logo">
        <input class="menu-btn" type="checkbox" id="menu-btn" />
        <label class="menu-icon" for="menu-btn"><span class="navicon"></span></label>
        <div class="menu">
            <li><a href="#Home" class="navbar-item">Home</a></li>
            <li><a href="#Pages" class="navbar-item">Pages</a></li>
            <li><a href="#Blog" class="navbar-item">Blog</a></li>
            <li><a href="#Portfolio" class="navbar-item">Portfolio</a></li>
            <li><a href="#Contacts" class="navbar-item">Contacts</a></li>
        </div>
        <div class="social-media">
            <li><a href="#" class="fa fa-facebook"></a></li>
            <li><a href="#" class="fa fa-twitter"></a></li>
            <li><a href="#" class="fa fa-linkedin"></a></li>
            <li><a href="#" class="fa fa-google"></a></li>
        </div>

    </header>
</template>

<script>
    export default {
        name: 'Header',
        props: {
            msg: String
        }
    }
</script>