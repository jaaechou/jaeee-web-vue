<script lang="ts">
import Logo from './assets/icons/logo.svg'
import Header from '@/components/Header/Header.vue'
import NavMenu from '@/components/NavMenu/NavMenu.vue'

export default {
  components: { NavMenu, Header },
  data() {
    return {
      Logo
    }
  }
}
</script>

<template>
  <div class="app">
    <NavMenu />
    <Header />
  </div>
</template>

<style scoped>
@import 'App.style.scss';
</style>
