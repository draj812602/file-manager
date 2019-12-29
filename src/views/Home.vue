<template>
  <div class="home">
    
    <HelloWorld />
    <hr>
    <Recent />
    <hr>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/Navbar.vue'
import Recent from '@/components/Recent.vue'

export default {
  name: 'home',
  components: {
    HelloWorld,
    Recent
  }
}
</script>
