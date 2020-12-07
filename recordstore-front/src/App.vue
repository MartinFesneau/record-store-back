<template>
  <div id="app">
    <the-header></the-header>
    <router-view/>
  </div>
</template>

<script>
import TheHeader from './components/UI/TheHeader.vue'

export default {
  name: 'App',
  components: {
    TheHeader
  }
}
</script>
