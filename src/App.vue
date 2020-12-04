<template>
  <div id="app">
    <header-block/>
    <rent-block></rent-block>
  </div>
</template>

<script>
import HeaderBlock from './components/header.vue'
import RentBlock from './components/rent.vue'
export default {
  name: 'App',
  components: {
    HeaderBlock,
    RentBlock
  }
}
</script>

<style>
#app {
  
}
</style>