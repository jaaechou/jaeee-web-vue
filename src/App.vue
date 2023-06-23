<script lang="ts">
import Logo from './assets/icons/logo.svg'

export default {
  components: {},
  data() {
    return {
      Logo
    }
  }
}
</script>

<template>
  <div class="app">
    <header>
      <div><img alt="logo" :src="Logo" /></div>
    </header>
  </div>
</template>

<style scoped>
@import 'App.style.scss';
</style>
