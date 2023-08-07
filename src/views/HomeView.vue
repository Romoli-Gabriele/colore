<template>
  <canvas id="tela" height="100" width="100" style="border:1px solid #000000;" :class="color">
  </canvas>
</template>

<script>

export default {
  name: 'HomeView',
  data () {
    return {
      color: 'red'
    }
  },
}
</script>

<style scoped>
.red {
  background-color: rgb(37, 117, 97);
}
</style>

