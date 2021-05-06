<template>
    <header class="header">
        <img src="../assets/logo.png" class="navbar-logo">
        <input class="menu-btn" type="checkbox" id="menu-btn" />
        <label class="menu-icon" for="menu-btn"><span class="navicon"></span></label>
        <div class="menu">
            <li><a href="#home" class="navbar-item">HOME</a></li>
            <li><a href="#about" class="navbar-item">ABOUT</a></li>
            <li><a href="#skills" class="navbar-item">MY SKILLS</a></li>
            <li><a href="#portfolio" class="navbar-item">PORTFOLIO</a></li>
            <li><a href="#contact" class="navbar-item">CONTACTS</a></li>
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