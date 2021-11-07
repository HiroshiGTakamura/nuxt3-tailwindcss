<script setup>
const props = defineProps({
	src: String,
	title: String,
	subtitle: String,
});
</script>
<template>
	<div class="flex flex-col items-center justify-center p-10">
		<div class="flex flex-col items-center w-64 p-3 border border-gray-300 rounded-sm">
			<GridImage class="mb-3 h-52 w-52" :src="props.src" />
			<h1 class="text-xl font-bold">{{ props.title }}</h1>
			<h2 class="text-justify text-gray-600">{{ props.subtitle }}</h2>
		</div>
	</div>
</template>
