<template>
  <div id="app">
    <container>
      <button text='test'>
    <container>
</template>

<script>
import Button from './components/Button'
import Container from './components/Container'

export default {
  components: {
    Button,
    Container
  }
}
</script>

<style>
html {
  height: 100%;
}

body {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}

#app {
  color: #2c3e50;
  margin-top: -100px;
  max-width: 600px;
  font-family: Source Sans Pro, Helvetica, sans-serif;
  text-align: center;
}

#app a {
  color: #42b983;
  text-decoration: none;
}

.logo {
  width: 100px;
  height: 100px
}

.button {
  border: solid 2px;
}
</style>
