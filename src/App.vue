<template>
  <div id="app">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <WinningNumbers />
        </div>
        <div class="col-md-6">
          <NumbersContainer />
        </div>
      </div>
      <div class="row">
        <div class="col-md-6">
          <TicketContainer />
        </div>
        <div class="col-md-6">
          <AddTicket />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NumbersContainer from './components/section_1/NumbersContainer.vue'
import AddTicket from '@/components/section_2/AddTicket.vue'
import TicketContainer from '@/components/section_4/TicketContainer.vue'
import WinningNumbers from '@/components/section_3/WinningNumbers.vue'

export default {
  name: 'app',
  components: {
    NumbersContainer,
    AddTicket,
    TicketContainer,
    WinningNumbers
  }
}
</script>

<style>

</style>
