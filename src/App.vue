<template>
  <div id="app">
    <Navbar />
    <div id="app-container">
      <router-view/>
    </div>
  </div>
</template>

<script>
// add navbar
import Navbar from '@/components/Navbar.vue'

  export default {
    name: 'app',
    components: {
      Navbar
    }
  }
</script>
