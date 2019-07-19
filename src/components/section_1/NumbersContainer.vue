<template>
  <div id="numbers-container">
    <div class="container">
      <div class="row">
        <div class="col-md-6 ml-auto">
          <div class="row">
            <NumberItem class="mb-3" msg="Sending text from parent component" v-for="item in 30" v-bind:key="item.id"/>
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
      item: null
    }
  }
}
</script>

<style scoped>
</style>
