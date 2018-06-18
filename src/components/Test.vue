<template>
  <div class="test">
    <npm-publish />
  </div>
</template>

<script>

//测试使用我们发布的模块
import NpmMyPublish from 'npm-my-publish'


export default {
  name: 'Test',
  data () {
    return {
      
    }
  },
  components:{
    'npm-publish':NpmMyPublish
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
