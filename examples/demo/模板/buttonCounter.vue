
<template>
  <button v-on:click="count++">
    你已点击 <span class="counter">{{ count }}</span> 次数.
  </button>
</template>
<script>
export default {
  data: function () {
    return {
      count: 0
    }
  }
}
</script>
<style scoped>
  #app {
    position: fixed;
    top: 200px;
    left: 400px;
    right: 100px;
    bottom: 100px;
  }
  .counter {
    font-size: 30px;
    color: red;
  }
</style>