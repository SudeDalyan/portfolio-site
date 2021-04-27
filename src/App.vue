<template>
<div class="row">
<div class="col-12 header">
<Header />
</div>
<div class="col-12 home">
  <Home/>
</div>
<div class="col-12 pages">
<Pages />
</div>
</div>
</template>


<script>
import Home from './components/Home.vue'
import Header from './components/Header.vue'
import Pages from './components/Pages.vue'


export default {
  name: 'App',
  components: {
    Home,
    Header,
    Pages,

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
.row{
width: 100%;}
.home{
margin-top:100px;}
</style>
