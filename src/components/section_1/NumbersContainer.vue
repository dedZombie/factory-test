<template>
  <div id="numbers-container">
    <div class="container">
      <div class="row">
        <div class="col-md-6 ml-auto">
          <div class="row">
            <NumberItem class="col-md-2 mb-3" v-for="n in 30" :key="n" :value="n" />
          </div>
          <div class="row">
            <AddTicket />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NumberItem from './NumberItem.vue'
import AddTicket from '@/components/section_2/AddTicket.vue'

export default {
  name: 'NumbersContainer',
  components: {
    NumberItem,
    AddTicket
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
