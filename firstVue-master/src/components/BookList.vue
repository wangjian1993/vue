<template>
	<li class="book_li">
		<div class="book_img">
			<img src="../assets/img/reserve_04.png" alt="" />
		</div>
		<div class="book_text">
			<p>{{book_name}}</p>
			<p>{{book_munu}}</p>
			<p>{{book_pirck}}</p>
		</div>
	</li>
</template>
<style scoped>
	.book_li{
		padding:0.3rem;
		height: 2.5rem;
	}
	.book_img{
		width: 45%;
		height: 2.5rem;
		float: left;
	}
	.book_text{
		width: 54%;
		height: 2.5rem;	
		float: left;
	}
	.book_img>img{
		width: 100%;
		height: 2.5rem;
	}
	.book_text>p{
		padding-top: 0.4rem;
		padding-left: 0.2rem;
		font-size: 0.36rem;
	}
</style>
<script>
	export default {  
        // 接收父组件传过来的以下几个属性  
        props: ['book_name', 'book_munu', 'book_pirck'],  
    }  
</script>