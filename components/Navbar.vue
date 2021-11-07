<script setup>
const drop = ref(false);
</script>
<template>
	<div class="fixed z-10 flex items-center justify-between w-full h-16 px-6 py-3 bg-white border-b border-gray-300 drop-shadow-md">
		<NuxtLink to="/" class="flex h-8 px-1 text-xl font-bold bg-gray-100 border-2 border-black rounded-full">
			<img class="h-5 m-1" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRg0o3fnDRmdhBz2uUkBtj3r-96ICq4bj1Ftw&usqp=CAU" />
			<h1 class="text-xl">Oficina Online</h1>
			<img class="h-5 m-1" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRg0o3fnDRmdhBz2uUkBtj3r-96ICq4bj1Ftw&usqp=CAU" />
		</NuxtLink>
		<h1>
			<span v-if="$route.fullPath == '/'" class="location">Home</span>
			<span v-if="$route.fullPath == '/sobrenos'" class="location">Sobre Nós</span>
			<span v-if="$route.fullPath == '/servicos'" class="location">Serviços</span>
			<span v-if="$route.fullPath == '/produtos'" class="location">Produtos</span>
			<span v-if="$route.fullPath == '/contato'" class="location">Contato</span>
		</h1>
		<button class="h-full bg-white" @click="drop = !drop">
			<MenuIcon />
		</button>
		<div class="absolute flex flex-col p-4 bg-white border border-gray-300 rounded-md right-10 top-10 drop-shadow-md" v-if="drop">
			<NuxtLink @click="drop = !drop" class="drop-item" to="/sobrenos">Sobre Nós</NuxtLink>
			<NuxtLink @click="drop = !drop" class="drop-item" to="/servicos">Serviços</NuxtLink>
			<NuxtLink @click="drop = !drop" class="drop-item" to="/produtos">Produtos</NuxtLink>
			<NuxtLink @click="drop = !drop" class="drop-item" to="/contato">Contato</NuxtLink>
		</div>
	</div>
	<div class="pt-16"></div>
</template>
<style scoped>
.drop-item {
	@apply transform hover:-translate-y-1 transition-transform px-4 py-2 text-left font-semibold bg-white hover:bg-gray-200;
}
.location {
	@apply drop-shadow-md font-semibold;
}
</style>
