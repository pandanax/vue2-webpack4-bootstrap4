<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li>
        <a href="/about">
          About
        </a>
      </li>
      <li>
        <a href="/login">
          Login
        </a>
      </li>

    </ul>
    <h2>New starter included:</h2>
    <ul>
      <li>
        "bootstrap": "^4.3.1",
      </li>
      <li>
        "vue": "^2.6.10",
      </li>
      <li>
        "bootstrap-vue": "^2.0.0",
      </li>
      <li>
        "webpack": "^4.33.0",
      </li>
      <li>
        "@babel/core": "^7.4.5",
      </li>
    </ul>

    <h2>Enjoy the fresh stuff by @pandanax</h2>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Webpack+Bootsrap+Vue SPA'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
