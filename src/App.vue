<template>
  <div id="app">
    <FirstTitle/>
    <MyHero/>
  </div>
</template>

<script>
import FirstTitle from './components/FirstTitle.vue'
import MyHero from './components/MyHero.vue'

export default {
  name: 'App',
  components: {
    FirstTitle,
    MyHero,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
