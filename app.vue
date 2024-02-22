<script setup>
const initString = ref("Hello World");
console.log(initString.value);
</script>
<template>
  <div class="container mx-auto">
    <header
      class="h-12 flex justify-center items-center bg-green-400 rounded-md p-12 my-12"
    >
      <h1 class="text-center font-bold text-3xl text-white">Vue Tutorial</h1>
    </header>
    <main>
      <p>Variable Declaration</p>
      <p class="text-2xl font-bold">
        {{ initString }}
      </p>
    </main>
  </div>
</template>
