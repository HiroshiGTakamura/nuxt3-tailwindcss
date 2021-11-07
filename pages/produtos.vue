<script setup>
const api = await $fetch("https://api.chucknorris.io/jokes/random");
</script>
<template>
	<div>
		<h1>
			{{ api.value }}
		</h1>
		<!-- <h1>{{ api.name }}</h1>
		<img :src="api.sprites.front_default" />
		<img :src="api.sprites.front_shiny" /> -->
	</div>
</template>
