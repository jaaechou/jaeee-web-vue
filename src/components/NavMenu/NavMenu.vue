<script lang="ts">
export default {
  data() {
    return {
      menuItems: [
        {
          label: '首页',
          icon: 'home',
          router: 'home'
        },
        {
          label: '首页',
          icon: 'home',
          router: 'home'
        }
      ]
    }
  }
}
</script>

<template>
  <div class="navMenu">
    <div v-for="(item, index) in menuItems" :key="index">{{ item.label }}</div>
  </div>
</template>

<style>
@import './NavMenu.style.scss';
</style>
