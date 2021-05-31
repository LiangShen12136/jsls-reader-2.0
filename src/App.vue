<template>
  <div id="app">
	<tab-bar></tab-bar>
	<router-view></router-view>
  </div>
</template>

<script>
const TabBar=()=>import('./components/TabBar.vue');

export default {
  name: 'app',
  components: {
    TabBar
  }
}
</script>
	
<style>
	@import url('./assets/css/base.css');
</style>
