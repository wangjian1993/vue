<template>
	<div class="yuding">
		<yuding-header></yuding-header>
		<h1>预定</h1>
		<home-footer></home-footer>
	</div>
</template>
<style>
	.container {
		max-width: 640px;
		margin: 0 auto;
		overflow-x: hidden;
	}
	.content{
		padding-bottom: 50px;
	}
	.cont_ul {
		padding-top: 0.05rem;
		margin: 0 -0.12rem;
	}
	.cont_ul:after {
		content: "";
		display: block;
		width: 0;
		height: 0;
		clear: both;
	}
</style>
<script>
	// 导入要用到的子组件
	import YudingHeader from '../components/YudingHeader'
	import HomeFooter from '../components/HomeFooter'
	
		// 在components字段中，包含导入的子组件
	export default {
		components: {
			YudingHeader,
			HomeFooter
		}
	}
</script>