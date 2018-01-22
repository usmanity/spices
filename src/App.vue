<template>
  <div id="app">
    <router-view/>
    <link href="https://fonts.googleapis.com/css?family=Catamaran:800|Heebo:500,700,800,900|Neuton|Vollkorn" rel="stylesheet">
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
h1 {
  margin: 50px 0;
}
#app {
  font-family: Catamaran, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
