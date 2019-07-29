<template>
  <div id="number-item">
    <button class="number-btn" :class="{ 'selected': isSelected }" @click="selectNum">{{ value }}</button>
  </div>
</template>

<script>

export default {
  name: 'NumberItem',
  props: ['value'],
  data() {
    return {
      isSelected: false
    }
  },
  methods: {
    selectNum: function() {
      this.isSelected = !this.isSelected
    }
  }
}
</script>

<style scoped>
.number-btn {
  width: 50px;
  height: 50px;
  border-radius: 50px;
  background-color: lightblue;
  color: white;
  font-size: 22px;
  border: 0;
  outline: none;
}
.selected {
  background-color: lightgreen;
}
</style>
