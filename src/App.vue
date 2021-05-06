<template>
<div class="row">
<div class="col-12 header" id="header">
<Header />
</div>
<div class="col-12 home" id="home">
  <Home/>
</div>
<div class="col-12 about" id="about">
<About />
</div>
<div class="col-12 skills" id="skills">
<Skills />
</div>
<div class="col-12 portfolio" id="portfolio">
<Portfolio />
</div>
<div class="col-12 contact" id="contact">
<Contact />
</div>
<div class="col-12 footer" id="footer">
<Footer />
</div>
</div>
</template>


<script>
import Home from './components/Home.vue'
import Header from './components/Header.vue'
import About from './components/About.vue'
import Skills from './components/Skills.vue'
import Portfolio from './components/Portfolio.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Home,
    Header,
    About,
    Skills,
    Portfolio,
    Contact,
    Footer

  }
}
</script>

<style>
div {
  font-family: 'Times New Roman', Times, serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
.row{width: 100%;}
.home{margin-top:75px;}
.about{margin-top:100px;}
.skills{margin-top: 100px;}
.portfolio{margin-top: 50px;}
.contact{margin-top: 100px;}
.footer{margin-top: 50px;}
</style>
