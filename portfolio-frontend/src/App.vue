<template>
<div>
  <NavBar></NavBar>
  <Body></Body>
  <Footer></Footer>
</div>
</template>
<style>
</style>
<script>
  import NavBar from './components/NavBar.vue';
  import Body from './components/Body.vue';
  import Footer from './components/Footer.vue';
  export default
  {
    name : 'App',
    data(){
      return{}
    },
    components : {
      NavBar,Body,Footer
    }
  }
</script>
