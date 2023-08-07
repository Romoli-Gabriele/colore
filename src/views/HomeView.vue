<template>
  <br>
  <canvas id="tela" :height="h" :width="w" :style="'background-color: '+color">
  </canvas>
  <br>
  <button class="btn">SI</button>
  <button class="btn">NO</button>
  <br>
  <label>height</label>
  <input type="number" class="input" v-model="h">
  <label>width</label>
  <input type="number" class="input" v-model="w">
  <label>time</label>
  <input type="number" class="input" v-model="t">
  <br>
</template>

<script>

export default {
  name: 'HomeView',
  data () {
    return {
      h: 500,
      w: 500,
      t: 1000,
      color: 'rgb(500, 500, 50)',
    }
  },
}
</script>

<style scoped>
.btn{
  background-color: rgb(119, 119, 119);
  color: white;
  border: solid 1px black;
  padding: 15px 32px;
  margin: 3px;
  text-align: center;
  text-decoration: none;
  font-size: 16px;
}
.input{
  border: solid 1px black;
  width: 50px;
  height: 20px;
  margin: 3px;
  background-color: rgb(119, 119, 119);

}
</style>

