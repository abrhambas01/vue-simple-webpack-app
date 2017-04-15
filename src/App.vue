<template>
	<div id="app">
		<app-message>Welcome to your app</app-message>
	</div>
</template>
<script>
	import Message from './components/Message.vue';
	export default {
		components : { 
			'app-message' : Message 
		}
	}
</script>
<style>
	#app {
		margin : 27px;
		background-color : #eaeaea;
		color : black;
	}
</style>
