<!-- Detail.vue -->
<template>
	<div class="detail">
		<detail-header></detail-header>
		<img src="../assets/img/home_06.png" alt="">
		<p>觐海台私人俱乐部，毗邻招商局半山别墅鲸山觐海，与港湾大道交界，弧形主体建筑构成令人瞩目的地标</p>
		<p>海归文化与现代时尚的都市格调在此完美融合，相得益彰。秉承“一脉相承，殷勤好客的服务”理念，觐海台私人俱乐部以低调奢华又具个性化的方式关注每一个细微之处，使每一次到来都成为令</p>
		<img src="../assets/img/home_07.png" alt="" />
		<p>觐海台私人俱乐部，毗邻招商局半山别墅鲸山觐海，与港湾大道交界，弧形主体建筑构成令人瞩目的地标。</p>
		<img src="../assets/img/home_01.png" alt="" />
		<img src="../assets/img/home_06.png" alt="" />
		<p>海归文化与现代时尚的都市格调在此完美融合，相得益彰。秉承“一脉相承，殷勤好客的服务”理念，觐海台私人俱乐部以低调奢华又具个性化的方式关注每一个细微之处，使每一次到来都成为令</p>
	</div>
</template>
<style scoped>
	.detail {
		padding: 0.24rem;
		font-size: 12px;
		background: #FFFFFF;
	}
	img {
		display: block;
		width: 100%;
		height: 4.5rem;
		margin: 0 auto 0.2rem;
	}
	
	p {
		font-size: 18px;
		line-height: 0.5rem;
		text-align: justify;
		padding-bottom: 0.24rem;
		font-family: "微软雅黑";
	}
</style>
<script>
	import DetailHeader from '../components/DetailHeader'

	export default {
		components: {
			DetailHeader
		}
	}
</script>