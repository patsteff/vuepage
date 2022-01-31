<template>
  <div id="nav">
    <Navigation :message="message" />
  </div>
  <router-view />
</template>

<script>
import Navigation from './components/Navigation'
export default {
  name: 'app',
  components: { Navigation },
  data () {
    return {
      message: 'You loaded this page on ' + new Date().toLocaleString()
    }
  }
}
</script>

<style>
</style>
