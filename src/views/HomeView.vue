<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App Kai"/>
    <ContactFooter />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import ContactFooter from '@/components/footerInfo.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    ContactFooter
  }
}
</script>
