<script setup lang="ts">
import Navbar from '../components/navbar.vue';
</script>

<template>
  <div>
    <Navbar/>
    <main>
      <slot></slot>
    </main>
  </div>
</template>

<style scoped>

</style>