<template>
  <header class="homeheader">
    <div class="homeheader-box">
    	<span></span>
    	<div>家里交给它 夏日浪到飞起→</div>
    </div>
    <div class="homeheader-nav">
    	<div>
    		nav
    	</div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'homeheader',
  data () {
    return {
    
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.homeheader{
	width:100%;
	height:240px;
	.homeheader-box{
		height:123px;
		width:100%;
		margin:0 auto;
		
		padding:21px 28px 0 28px;
		position:relative;
		border-bottom:1px solid #A9A9A9;
		span{
			position:absolute;
			left:50px;
			top:40px;
			display: block;
			height:42px;
			width:42px;
			background:url(../../img/icon/icon1.png) no-repeat;
		}
		div{
			background:#e6e6e6;
			height:81px;
			padding:13px 26px 13px 78px;
			color:#A9A9A9;
			border-radius:14px;
		}
	}
}
	
</style>
