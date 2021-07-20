<template>
  <div id="app">
    <HelloWorld />
    <Login />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Login from './components/Login.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Login
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
html, body {
  width: 100%;
  height: 100%;
  min-width: 1300px
}
ul {
  list-style: none;
}
input:focus {
  outline: none;
}
</style>
