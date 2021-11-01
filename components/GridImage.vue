<script setup>
const props = defineProps({
	src: String,
});
</script>
<template>
	<div>
		<img class="object-cover object-center w-full h-full rounded-md" :src="props.src" />
	</div>
</template>
