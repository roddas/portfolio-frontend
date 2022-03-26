<template>
<div>
  <NavBar></NavBar>
  <Body></Body>
</div>
</template>
<style>
</style>
<script>
  import NavBar from './components/NavBar.vue';
  import Body from './components/Body.vue';
  export default
  {
    name : 'App',
    data(){
      return{}
    },
    components : {
      NavBar,Body
    }
  }
</script>
