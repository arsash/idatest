<template>
  <div id="app">
    <header-block/>
    <rent-block>
      <RentItem>dfgdfgdfg</RentItem>
    </rent-block>
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
