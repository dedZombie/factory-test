<template>
  <div id="number-item">
    1
  </div>
</template>

<script>

export default {
  name: 'NumberItem',
  props: {
    msg: String
  }
}
</script>

<style scoped>
#number-item {
  background-color: lightgreen;
  border-radius: 50%;
  color: white;
  text-align: center;
  font-size: 22px;
  flex: 0 0 16.6666667%;
  max-width: 16.6666667%;
}
</style>
