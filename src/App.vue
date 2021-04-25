<template>
<div>
  <Header/>
  <Home/>
</div>
</template>


<script>
import Header from './components/Header.vue'
import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    Header,
    Home,
  }
}
</script>

<style>
div {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
