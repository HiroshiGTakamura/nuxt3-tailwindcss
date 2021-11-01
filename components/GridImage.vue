<script setup>
  const props = defineProps({
    src: String
  });
</script>
<template>
  <div>
    <img class="rounded-md w-full h-full object-cover object-center" :src="props.src"/>
  </div>
</template>