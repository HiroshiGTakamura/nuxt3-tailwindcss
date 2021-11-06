<script setup>
const props = servs({
	src: String,
	title: String,
	subtitle: String,
});
</script>
<template>
	<div class="flex w-10 h-16 p-5 border border-gray-400 drop-shadow-md round-sm">
		<img class="object-cover object-center w-8 h-12 round-sm" :src="props.src" />
		<h1 class="font-semibold">
			{{ props.title }}
		</h1>
		<h2 class="text-gray-600">
			{{ props.subtitle }}
		</h2>
	</div>
	<CustomFooter />
</template>
