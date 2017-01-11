<!-- List.vue -->
<template>
	<li class="sec_li">
		<router-link to="/detail" class="lp_li_a">
			<div class="lp_li_imgWrap">
				<img :src="img" alt="">
			</div>
			<p class="lp_li_name">{{ title }}</p>
			<p class="lp_li_price">{{ price }}</p>
		</router-link>
	</li>
</template>

<style scoped>
	.sec_li {
		float: left;
		width: 100%;
	}
	.lp_li_a {
		display: block;
		margin: 0 0.05rem;
		background: #fff;
	}
	.lp_li_imgWrap {
		padding: 0.24rem 0;
	}
	.lp_li_imgWrap > img {
		width: 100%;
		height: 4.5rem;
	}
	.lp_li_name {
		height: 0.5rem;
		line-height: 0.5rem;
		font-size: 16px;
		color: #000;
		margin-left: 10px;
	}
	.lp_li_price {
		color: #000;
		height: 0.5rem;
		line-height: 0.5rem;
		font-size: 16px;
		margin-left: 10px;
	}
</style>

<script>
	export default {  
        // 接收父组件传过来的以下几个属性  
        props: ['price', 'title', 'img'],  
    }  
</script>