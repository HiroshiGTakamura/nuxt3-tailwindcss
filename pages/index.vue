<template>
	<div>
		<div id="background" class="w-full h-96">
			<div class="flex flex-col items-center justify-center w-full h-full p-10 space-y-4 backdrop-filter backdrop-blur-sm md:flex-row md:space-x-8 md:space-y-0">
				<div class="grid h-48 grid-cols-3 grid-rows-2 gap-2 w-72">
					<GridImage class="col-span-2 row-span-2" src="https://images.unsplash.com/photo-1615906655593-ad0386982a0f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=25" />
					<GridImage src="https://images.unsplash.com/photo-1429772011165-0c2e054367b8?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1170&q=25" />
					<GridImage src="https://images.unsplash.com/photo-1619642751034-765dfdf7c58e?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1074&q=25" />
				</div>
				<div class="flex flex-col text-center md:text-left">
					<h1 class="text-4xl font-bold text-white drop-shadow">Sua oficina mecânica preferida.</h1>
					<h2 class="text-2xl text-gray-400">Somos a escolha certa para seu automóvel!</h2>
				</div>
			</div>
		</div>
		<div class="flex justify-center px-0 md:px-32 lg:px-72">
			<div class="flex flex-col h-full p-8 mx-4 border-l-2 border-r-2 border-gray-300 drop-shadow-md md:flex-row">
				<p class="pr-8 text-justify">
					Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eveniet excepturi dolores animi aspernatur aperiam quas numquam, assumenda iste voluptatem omnis explicabo voluptates error quidem ipsam fugit nesciunt ab pariatur, illum molestiae nisi voluptatibus recusandae? Eius, laboriosam odio ut est cumque, quisquam natus expedita ullam dolor sint vitae illum, dolore nulla id similique alias quaerat illo ea dicta labore aperiam! Nostrum modi voluptate consequuntur ipsam voluptates odit
					dicta et dolorem ullam eius quaerat quod sed, accusamus necessitatibus praesentium quo aspernatur delectus non quisquam alias! Voluptatem optio sint atque, tempora officia incidunt et ipsam. Odio unde quaerat dolorem, eius magnam vero reiciendis?
					<br />
					<br />
					Lorem ipsum, dolor sit amet consectetur adipisicing elit. Adipisci provident quibusdam, voluptates natus sed enim quo fugiat? Fugiat itaque distinctio delectus earum aperiam voluptatem magni.
				</p>
				<div class="mt-5 md:mt-0">
					<div class="relative h-auto p-4 border-2 border-gray-600 rounded-lg">
						<legend class="absolute px-2 text-xl font-semibold bg-white border-2 border-gray-600 rounded-lg -top-4 left-4">Lorem ipsum</legend>
						<p class="text-justify">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas quos provident nam quae animi odit mollitia accusamus vel eos optio, commodi temporibus perferendis velit totam hic possimus itaque repellat sequi veritatis soluta voluptatem nisi facilis. Repellendus, hic totam doloremque atque magni perferendis facere quia ipsum sunt fugiat, voluptatibus velit consectetur.</p>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>
<style scoped>
#background {
	background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("https://images.unsplash.com/photo-1517524206127-48bbd363f3d7?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1074&q=5");
}
</style>
