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
</div>
</template>


<script>
import Home from './components/Home.vue'
import Header from './components/Header.vue'
import About from './components/About.vue'
import Skills from './components/Skills.vue'


export default {
  name: 'App',
  components: {
    Home,
    Header,
    About,
    Skills,

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
</style>
