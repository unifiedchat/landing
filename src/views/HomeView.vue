<template>
  <main class="pb-8">
    <Hero />
    <InformationCard />
    <GetStarted />
    <Footer />
  </main>
</template>

<script setup lang="ts">
import Hero from "@/components/Hero.vue";
import InformationCard from "@/components/InformationCard.vue";
import GetStarted from "@/components/GetStarted.vue";
import Footer from "@/layout/Footer.vue";
</script>
