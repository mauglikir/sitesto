<template>
  <div id="app">
    <h1>Hello World!</h1>
    <stoMainContent></stoMainContent>
  </div>
</template>

<script>
import stoMainContent from './components/content-sto'

export default {
  name: 'App',
  components: {
    stoMainContent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
