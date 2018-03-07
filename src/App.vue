<template>
  <div id="app">
    <Header/>
  </div>
</template>

<script>
import Header from './components/common/Header/Header'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>
<!--@import './styles/icon.less';-->
<style>

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
