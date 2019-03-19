<!-- template只能向外暴露一个标签，所有只能在最外层包裹一个标签 -->
<!-- 单页应用，由js进行渲染，优点：界面切换快，缺点：首屏时间稍慢，seo差 -->
<template>
	<div>
		<div class="home">home</div>
		<router-link  to="/list" class="home">列表页</router-link>
	</div>
</template>

<script>
export default {
	name: 'home'
}
</script>
<style>
	.home{
		font-size:50px;
	}
</style>