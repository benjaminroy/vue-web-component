<template>
  <div id="app">
    <vue-tel-input v-model="phone"></vue-tel-input>
  </div>
</template>

<script>
import Vue from 'vue'
import VueTelInput from 'vue-tel-input'

Vue.use(VueTelInput)

export default {
  name: 'app',
  data() {
    return {
      phone: '',
    };
  },
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
