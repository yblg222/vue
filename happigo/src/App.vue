<template>
  <div id="app">
   
    <router-view></router-view>
    <nav-tab></nav-tab>
  </div>
</template>

<script>
import NavTab from './components/NavTab'
export default {
  name: 'app',
  components:{
  	NavTab
  }
}
</script>

<style lang="scss">
	
	@import './styles/reset.scss';
	

html,body,#app{
	height:100%;
	margin:0 ;padding:0;
	position:relative;
}
</style>


















































