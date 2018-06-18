<template>
  <div class="button">
	 <a href="javascript:;" :style="css"  @click="tips">{{text}}</a>
  </div>
</template>

<script>
export default {
  name: 'Button',
  data () {
    return {
    }
  },
  props:{
  	css:{
  		type:String,
  		default:"background-color:green;color:#fff"
  	},
  	text:{
  		type:String,
  		default:"按钮"
  	}
  },
  methods:{
  	tips(){
  		alert(this.text);
  	}
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	.button a{
		display: inline-block;
		padding: 10px 20px;
		border-radius: 3px;
	}
</style>
