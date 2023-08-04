<script lang="ts">
import Logo from '../../assets/icons/logo.svg'
import User from '../../assets/icons/user.svg'
export default {
  components: {},
  data() {
    return {
      Logo,
      User
    }
  }
}
</script>

<template>
  <div class="headerRoot">
    <img alt="logo" :src="Logo" />
    <div class="headerRight">
      <img alt="user" :src="User" />
      <span>jaaechou</span>
      <a>退出</a>
    </div>
  </div>
</template>

<style scoped>
@import 'Header.style.scss';
</style>
