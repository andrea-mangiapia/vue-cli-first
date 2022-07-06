<template>
  <div id="app">
    <!-- Title -->
    <MyFirstTitle msg="La mia prima app con Vue CLI!"/>
    <!-- Hero -->
    <MyFirstHero/>

  </div>
</template>

<script>
import MyFirstTitle from './components/MyFirstTitle.vue'
import MyFirstHero from './components/MyFirstHero.vue'

export default {
  name: 'App',
  components: {
    MyFirstTitle,
    MyFirstHero
  }
}
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
