<template>
  <NavBar/>
  <router-view/>
</template>

<script>

  import NavBar from './components/NavBar.vue'

  export default {
    components : {
      NavBar
    }
  }

</script>

<style>
body{
  background-color: #2f3542;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #f1f2f6;
  max-width: 800px;
  margin: 0 auto;
}

</style>

