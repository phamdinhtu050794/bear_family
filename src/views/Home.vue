<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div> -->
  <Body></Body>
  </div>
</template>

<script>
// @ is an alias to /src
import Body from '@/components/Body.vue'

export default {
  name: 'Home',
  components: {
    Body
  }
}
</script>
