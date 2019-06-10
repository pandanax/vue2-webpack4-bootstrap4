<template>
  <div id="app">

    <div class="images">
      <div class="row">
        <div class="col-md-4">
          <img src="./assets/logo.png">
        </div>
        <div class="col-md-4">
          <img src="https://getbootstrap.com/docs/4.3/assets/brand/bootstrap-solid.svg">
        </div>
        <div class="col-md-4">
          <img src="https://webpack.js.org/d19378a95ebe6b15d5ddea281138dcf4.svg">
        </div>
      </div>

    </div>
    <router-view/>
  </div>
</template>

<script>
  export default {
    name: 'App'
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
  .images {
    margin: auto;
    max-width: 240px;
  }
  .images img{
    width: 64px;
    height: auto;
  }
</style>
