<template>
  <img alt="Vue logo" src="./assets/logo.png">
</template>

<script>
import {defineComponent} from 'vue';

import './VidyoClient'

export default defineComponent({
  name: 'App',
  components: {
  },
  mounted() {
    console.log(window.VidyoClientLib)
  }
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
