<template>
<div id="app">
	<el-container style="width: 100%; border: solid 1px red;">
		<el-aside width="20%" style="border: solid 1px blue;">
			侧边栏
		</el-aside>

		<el-container style="border: solid 1px blue;">
			<el-header style="border: solid 1px blue;">
				顶部栏
			</el-header>

			<el-main style="border: solid 1px blue;">
				主要内容
			</el-main>
		</el-container>
	</el-container>
</div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
    name: 'app',
    components: {
        // HelloWorld
    }
}
</script>

<style lang="scss">
#app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}



</style>
