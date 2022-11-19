<template>
    <v-app>
    <v-main>
  <HelloWorld />
  </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
 a{
    text-decoration: none;
  }
</style>
