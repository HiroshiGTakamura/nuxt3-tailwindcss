<template>
  <div>
    <Navbar/>
    <div id="background" class="h-96 w-screen">
      <div class="p-10 w-full h-full backdrop-filter backdrop-blur-sm flex-col md:flex-row flex items-center justify-center space-y-4 md:space-x-8 md:space-y-0">
        <div class="grid grid-cols-3 grid-rows-2 h-48 w-72 gap-2">
          <GridImage class="row-span-2 col-span-2" src="https://images.unsplash.com/photo-1615906655593-ad0386982a0f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=50" />
          <GridImage src="https://images.unsplash.com/photo-1429772011165-0c2e054367b8?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1170&q=50" />
          <GridImage src="https://images.unsplash.com/photo-1619642751034-765dfdf7c58e?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1074&q=50" />
        </div>
        <div class="flex flex-col text-center md:text-left">
          <h1 class="text-4xl font-bold text-white drop-shadow">
            Sua oficina mecânica preferida.
          </h1>
          <h2 class="text-2xl text-gray-400">
            Somos a escolha certa para seu automóvel!
          </h2>
        </div>
      </div>
    </div>
    <div class="px-12 md:px-72 flex justify-center">
      <div class="drop-shadow-md border-l-2 border-b-2 border-r-2 border-gray-300 h-full mx-4">
        <div class="flex gap-5 py-12 px-5 ">
          <h1 class="text-justify">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eveniet excepturi dolores animi aspernatur aperiam quas numquam, assumenda iste voluptatem omnis explicabo voluptates error quidem ipsam fugit nesciunt ab pariatur, illum molestiae nisi voluptatibus recusandae? Eius, laboriosam odio ut est cumque, quisquam natus expedita ullam dolor sint vitae illum, dolore nulla id similique alias quaerat illo ea dicta labore aperiam! Nostrum modi voluptate consequuntur ipsam voluptates odit dicta et dolorem ullam eius quaerat quod sed, accusamus necessitatibus praesentium quo aspernatur delectus non quisquam alias! Voluptatem optio sint atque, tempora officia incidunt et ipsam. Odio unde quaerat dolorem, eius magnam vero reiciendis?
          </h1>
        </div>
      </div>
    </div>
    <CustomFooter/>
  </div>
</template>
<style scoped>
  #background{
    background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url("https://images.unsplash.com/photo-1517524206127-48bbd363f3d7?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1074&q=50");
  }
</style>