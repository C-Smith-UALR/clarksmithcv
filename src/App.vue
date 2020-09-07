<template>
  <div id="app">
    <Navbar></Navbar>
    <router-view/>
    <MedzoarFooter></MedzoarFooter>
  </div>
</template>

<style>
  /*h1 {*/
  /*  color: #434343;*/
  /*  font-family: 'Source Serif Pro', Georgia, serif;*/
  /*  font-size: 250%;*/
  /*}*/
/*#app {*/
/*  font-family: Avenir, Helvetica, Arial, sans-serif;*/
/*  -webkit-font-smoothing: antialiased;*/
/*  -moz-osx-font-smoothing: grayscale;*/
/*  text-align: center;*/
/*  color: #2c3e50;*/
/*}*/

/*#nav {*/
/*  padding: 30px;*/
/*}*/

/*#nav a {*/
/*  font-weight: bold;*/
/*  color: #2c3e50;*/
/*}*/

/*#nav a.router-link-exact-active {*/
/*  color: #42b983;*/
/*}*/
</style>
<script>
  import navbar from "./components/navbar";
  import medzoarFooter from "./components/footer"
  export default {
    components: {
      'MedzoarFooter': medzoarFooter,
      'Navbar': navbar
    }

  }
</script>