<template>
  <div id="app">
    <header_page v-for="menu in 5"></header_page>
  </div>
</template>

<script>
import block from "./Header.vue";
export default {
  name: 'app',
  data () {
    return {
      msg: "Welcome to Your Vue.js App"
    }
  },
  components: {
    'header_page': block
  }
}
</script>

<style>

</style>
