<template>
  <div class="container mx-auto space-x-4 flex items-center h-10 mb-10">
    <NuxtLink :to="{ name: 'a-empresa' }">Empresa</NuxtLink>
    <NuxtLink :to="{ name: 'servicos' }">Serviços</NuxtLink>
    <NuxtLink :to="{ name: 'produtos' }">Produtos</NuxtLink>
  </div>
</template>

<script>
export default {
  name: "BarraMenu",
};
</script>

<style>
</style>