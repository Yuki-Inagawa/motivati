<template>
  <div id="app">
    <header-component />
    <p>{{ message }}</p>
  </div>
</template>

<script lang="ts">
import HeaderComponent from './packs/components/header.vue'

export default {
  components: { HeaderComponent },
  data: function () {
    return {
      message: "Hello Vue!"
    }
  }
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
