 
<template>
  <div id="app">
    <nav-bar></nav-bar>
    <router-view></router-view>
  </div>
</template>

<script>
import NavBar from './pages/NavBar'
export default {
  name: 'app',
  data () {
    return {
      
    }
  },
  components: {
    'nav-bar': NavBar,
  }
}
</script>

<style>
</style>