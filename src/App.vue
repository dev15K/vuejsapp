<script setup lang="ts">
</script>

<template>
  <a-layout>
    <a-layout-header>
      <a-menu mode="horizontal">
        <a-menu-item>
          <router-link to="/">Home</router-link>
        </a-menu-item>
        <a-menu-item>
          <router-link to="/about">About</router-link>
        </a-menu-item>
      </a-menu>
    </a-layout-header>
    <a-layout-content>
      <router-view/>
    </a-layout-content>
  </a-layout>
</template>

<style scoped>

</style>
