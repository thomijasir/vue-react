<template>
	<div class="hello">
		<div class="vue">
			<p>Im From Vue Component</p>
		</div>
		<div class="react">
			<ReactComponent/>
		</div>
	</div>
</template>

<script>
import ReactComponent from '@/react/ReactComponent.jsx'

export default {
	name: 'HelloWorld',
	components: {
		ReactComponent,
	},
	data() {
		return {
			msg: 'Welcome to Your Vue.js App',
		}
	},
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
	display: flex;
	flex-direction: row;
	align-items: center;
	justify-content: center;
}
.vue {
	margin-right: 5px;
	padding: 10px;
	background-color: #388e3c;
	color: white;
	width: 250px;
	font-weight: bold;
}
.react {
	margin-left: 5px;
	padding: 10px;
	background-color: #0091ea;
	color: white;
	width: 250px;
	font-weight: bold;
}
</style>
