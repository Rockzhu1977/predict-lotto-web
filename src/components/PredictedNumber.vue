<!-- src/components/PredictedNumber.vue -->
<template>
  <div>
    <h2>Predicted Number</h2>
    <p>{{ predictedNumber }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      predictedNumber: Math.floor(Math.random() * 100) + 1
    }
  }
}
</script>