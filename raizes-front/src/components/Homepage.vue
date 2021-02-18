<template>
  <div id="Homepage">
    <Navbar /> 
  </div>
</template>

<script>
import Navbar from './Navbar'

export default {
  name: 'Homepage',
  props: {
    msg: String
  },
  components : {
    Navbar
  }
}
</script>

<style scoped>
.logo-container {
  display: inline;
}
</style>
