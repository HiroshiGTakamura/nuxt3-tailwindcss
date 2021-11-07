<script setup>
const produto = [
	{
		imagem: "https://images.tcdn.com.br/img/img_prod/732118/oleo_lubrificante_sintetico_10w_40_lubrax_avante_1l_227_1_20200116174820.jpg",
		nome: "Óleo lubrificante",
		categoria: "Óleos",
		preco: "24,59",
	},
	{
		imagem: "https://politintas.vteximg.com.br/arquivos/ids/159946-1000-1000/aromatizante-para-carro-proauto-breeze-amore-6-5g.jpg?v=636789329184700000",
		nome: "Aromatizante para carro",
		categoria: "Aromatizantes",
		preco: "11,30",
	},
	{
		imagem: "https://cf.shopee.com.br/file/fa7826577fbd0698efaeb0b7fda72785",
		nome: "Kit de tapetes 5 pcs.",
		categoria: "Acessórios",
		preco: "29,89",
	},
	{
		imagem: "https://a-static.mlcdn.com.br/618x463/capa-volante-massageador-37-cm-cabral/grifferepresentacao/51f1945a61bb11eb94cc4201ac1850d6/355e4df88e2603e7568865d94735ba70.jpg",
		nome: "Capa para volante azul",
		categoria: "Acessórios",
		preco: "30,00",
	},
	{
		imagem: "https://8694.cdn.simplo7.net/static/8694/sku/lubrificantes-automotivos-oleo-de-motor-0w30-shell-helix-ultra-api-sn-sintetico-1lt--p-1509543414255.jpg",
		nome: "Óleo para motor",
		categoria: "Óleos",
		preco: "61,49",
	},
	{
		imagem: "https://images.tcdn.com.br/img/img_prod/302929/1680_0_20180130112921.jpg",
		nome: "Macaco hidráulico",
		categoria: "Manutenção",
		preco: "159,99",
	},
	{
		imagem: "https://d27vawk0lzy7cb.cloudfront.net/catalog/product/cache/9225fc1d4c49b339af1429c8baa1360e/0/0/000000000089464795-a-0-4-3-000000000089464795_fo_1.jpg",
		nome: "Veda-pneu",
		categoria: "Manutenção",
		preco: "55,99",
	},
	{
		imagem: "https://images-americanas.b2w.io/produtos/01/00/img/1397138/3/1397138357_1GG.jpg",
		nome: "Suporte para celular",
		categoria: "Acessórios",
		preco: "24,00",
	},
];
</script>
<template>
	<div class="flex flex-col items-center justify-start">
		<div>
			<h1 class="text-4xl font-bold">Produtos</h1>
			<h2 class="text-lg text-gray-500">Conheça um pouco mais dos nossos produtos.</h2>
		</div>
		<div class="grid grid-cols-3 grid-rows-2 gap-4 p-3">
			<div v-for="item in produto" :key="item.nome">
				<div class="p-3 border rounded-md drop-shadow-lg">
					<img class="rounded-md w-52" :src="item.imagem" />
					<h1 class="text-base font-bold md:text-lg">{{ item.nome }}</h1>
					<h2 class="mb-3 text-sm text-gray-400">{{ item.categoria }}</h2>
					<h1 class="text-xl font-bold">R${{ item.preco }}</h1>
				</div>
			</div>
		</div>
	</div>
</template>
