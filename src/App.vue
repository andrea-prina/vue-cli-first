<template>

  <div id="app">
    <MainTitle/>
    <JumbotronBanner/>
  </div>

</template>

<script>
import MainTitle from "./components/MainTitle.vue"
import JumbotronBanner from "./components/JumbotronBanner.vue"

export default {
  name: 'App',
  components: {
    MainTitle,
    JumbotronBanner,
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
