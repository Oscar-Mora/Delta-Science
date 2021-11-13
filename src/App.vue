<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{ msg }}</h1>
    <h2>¡Hola! ¿Cómo te encuentras hoy?</h2>
    <h2>nombre-usuario</h2>
    <nav>
    <ul>
      <li><a href="" target="_blank">HOME</a></li>
      <li><a href="" target="_blank">RATINGS</a></li>
      <li><a href="" target="_blank">SENTIMENTS</a></li>
      <li><a href="" target="_blank">TO DO'S</a></li>
    </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Alfonso Marina'
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
  
}

nav {
  display:flex;
  text-align:left;
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
