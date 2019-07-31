<template>
  <div>
    <button class="action-btn" id="add-ticket" v-show="true">DODAJ TIKET</button>
    <button class="action-btn" id="play-game" v-show="false">ODIGRAJ</button>
  </div>
</template>

<script>
export default {
  name: 'AddTicket',
  data() {
    return {
      // 
    }
  }
}
</script>

<style>
.action-btn {
  width: 100%;
  font-size: 40px;
}
</style>
