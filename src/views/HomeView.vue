<script setup>
import HeroComponent from '@/components/HeroComponent.vue';
import TechnologieComponent from '@/components/TechnologieComponent.vue';
import PortfolioComponent from '@/components/PortfolioComponent.vue';
</script>

<template>
  <main>
    <HeroComponent/>
    <TechnologieComponent/>
    <PortfolioComponent><h2 class="title">PORTFOLIO</h2></PortfolioComponent>
  </main>
</template>
<style scoped>

.title {
  text-align: center;
  font-size: 3rem;
}
</style>
