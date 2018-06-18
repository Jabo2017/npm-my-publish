<template>
  <div id="app">
    <my-button :text="textName" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

import Button from './components/Button'

export default {
  name: 'App',
  components: {
    HelloWorld,
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
