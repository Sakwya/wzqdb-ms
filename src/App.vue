<template>
	<div id="app">
		<router-view></router-view>
	</div>
</template>

<script setup>
</script>

<style>
	* {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
	}

	#app {
		font-family: Avenir, Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		width: 100vw;
		height: 100vh;
		overflow: hidden;
		background: #f0f0f0;
	}

	a {
		text-decoration: none;
	}

	.container {
		width: 100vw;
		height: 100vh;
	}

	.icon {
		height: 1em;
		width: 1em;
	}
	.icon-inline{
		display: flex;
		align-items: center;
	}
</style>