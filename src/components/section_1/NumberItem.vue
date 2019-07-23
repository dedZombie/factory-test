<template>
  <div id="number-item">
    <button class="number-btn">{{ value }}</button>
  </div>
</template>

<script>

export default {
  name: 'NumberItem',
  props: ['value'],
  data() {
    return {
      //
    }
  }
}
</script>

<style scoped>
.number-btn {
  width: 50px;
  height: 50px;
  border-radius: 50px;
  background-color: lightgreen;
  color: white;
  font-size: 22px;
  border: 0;
  outline: none;
}
</style>
