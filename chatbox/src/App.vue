<template>
  <div id="app">
     <chat-box msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import ChatBox from './components/ChatBox.vue'

export default {
  name: 'App',
  components: {
    ChatBox
  }
}
</script>

<style>

</style>
