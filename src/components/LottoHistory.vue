<!-- src/components/LottoHistory.vue -->
<template>
  <div>
    <h2>Lottery History</h2>
    <ul>
      <li v-for="result in results" :key="result.id">
        {{ result.number }}
      </li>
    </ul>
  </div>
</template>

<script>
import axios from 'axios'

export default {
  data() {
    return {
      results: []
    }
  },
  async created() {
    const response = await axios.get('https://api.example.com/lotto-history')
    this.results = response.data
  }
}
</script>