<template>
  <div id="app">
    <front/>
    <back/>
  </div>
</template>

<script>
import front from './components/front.vue'
import back from './components/back.vue'
export default {
  name: 'App',
  components: {
    front,
    back
  }
}
</script>

<style>
</style>
