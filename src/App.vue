<template>
	<div id="app">
		<img src="/static/reactvue.png" alt="React Vue" width="300" height="300"/>
		<h1>Hello, Developer</h1>
		<router-view/>
	</div>
</template>

<script>
export default {
	name: 'App',
}
</script>

<style>
#app {
	font-family: 'Avenir', Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
</style>
