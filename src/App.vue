<script setup>
import LottoHistory from './components/LottoHistory.vue'
import PredictedNumber from './components/PredictedNumber.vue'
</script>

<template>
  <h1>Lotto History</h1>
  <LottoHistory />

  <h1>Predicted Number</h1>
  <PredictedNumber />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
</style>
