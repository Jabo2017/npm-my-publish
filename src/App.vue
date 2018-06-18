<template>
  <div id="app">
    <my-button :text="textName" />
    <Test />
  </div>
</template>

<script>
import Test from './components/Test'

import Button from './components/Button'

export default {
  name: 'App',
  components: {
    Test,
    'my-button':Button
  },
  data(){
    return {
      textName:"hello"
    }
  }
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
