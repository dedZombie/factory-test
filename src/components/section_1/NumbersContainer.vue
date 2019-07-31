<template>
  <div id="numbers-container">
    <div class="row">
      <NumberItem class="col-md-2 mb-3" v-for="n in 30" :key="n" :value="n" />
    </div>
  </div>
</template>

<script>
import NumberItem from './NumberItem.vue'

export default {
  name: 'NumbersContainer',
  components: {
    NumberItem
  },
  data() {
    return {
      n: null
    }
  }
}
</script>

<style scoped>
</style>
