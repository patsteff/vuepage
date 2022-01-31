<template>
  <div id="nav">
    <Navigation :msg="testMessage" />
  </div>
  <router-view />
</template>

<script>
import Navigation from './components/Navigation'
export default {
  name: 'app',
  components: { Navigation }
}
</script>

<style>
</style>
