<template>
  <div class="container xl:px-[72px] lg:px-[52px] px-20 pt-8">
    <Navbar />

    <div class="mt-28">
      <RouterView />
    </div>
  </div>
</template>

<script setup lang="ts">
import Navbar from "@/layout/Navbar.vue";
</script>
