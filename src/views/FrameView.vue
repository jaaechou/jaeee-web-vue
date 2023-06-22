<script lang="ts">
import Logo from '../assets/icons/logo.svg'
export default {
  data() {
    return {
      Logo
    }
  }
}
</script>

<template>
  <header>
    <div><img alt="logo" :src="Logo" /></div>
  </header>
</template>
