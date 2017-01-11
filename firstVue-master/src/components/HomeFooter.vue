<!-- HomeHeader.vue -->
<template>
	<footer class="footer">
		<router-link to="home" class="a">
			<div class="is1 tab"></div>
			<p>首页</p>
		</router-link>
		<router-link to="yuding" class="a">
			<div class="is2 tab"></div>
			<p>预定</p>
		</router-link>
		<router-link to="caidan" class="a">
			<div class="is3 tab"></div>
			<p>菜单</p>
		</router-link>
		<router-link to="wode" class="a">
			<div class="is4 tab"></div>
			<p>我的</p>
		</router-link>
	</footer>
</template>

<style>
.footer{
	width: 100%;
	overflow-x: hidden;
	position: fixed;
	bottom: 0;
	left: 0;
	background: #FFFFFF;
}
.a{
	display: block;
	width: 25%;
	text-decoration: none;
	color: #999;
	text-align: center;
	float: left;
}
.footer p {
	font-size:18px;
}
.footer>a>div{
	height: 32px;
	width: 100%;
}
.is1 {
	background: url(../assets/img/img1.png)no-repeat 50%;
	background-size: 32px;
}
.is2 {
	background: url(../assets/img/img2.png)no-repeat 50%;
	background-size: 32px;
}
.is3 {
	
	background: url(../assets/img/img3.png)no-repeat  50%;
	background-size: 32px;
}
.is4 {
	
	background: url(../assets/img/img4.png)no-repeat 50%;
	background-size: 32px;
}
</style>