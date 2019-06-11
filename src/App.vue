<template>
  <div id="app">
    <MainHeader />
    <div class="container-fluid">
      <router-view/>
    </div>
    <MainFooter />
  </div>
</template>

<script>
import MainHeader from './components/layouts/header/Main'
import MainFooter from './components/layouts/footer/Main'

export default {
  name: 'App',
  components: {
    MainHeader,
    MainFooter
  }
}
</script>

<style src="./assets/sass/app.scss" lang="sass"></style>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
