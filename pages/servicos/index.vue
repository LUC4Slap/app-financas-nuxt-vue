<template>
  <div>
    <div class="bg-gray-100">
      <BarraMenu />
    </div>

    <div>
      <div class="container mx-auto">
        <h1 class="text-lg font-bold">Serviços</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia ea
          velit placeat quibusdam corrupti, a maiores ut quidem laudantium
          repellat recusandae architecto dolore iure, ad ex magni asperiores
          ipsum. Laborum? Lorem ipsum dolor sit amet consectetur adipisicing
          elit. Neque nulla nam laudantium blanditiis! Esse delectus laborum
          beatae nobis commodi. Accusantium, molestias quas! Ducimus, inventore
          modi molestias laborum eum sint beatae? Lorem ipsum dolor sit amet
          consectetur adipisicing elit. Asperiores ipsum rerum optio quod,
          doloremque obcaecati nesciunt exercitationem tempora dolores,
          laboriosam eaque? Necessitatibus quibusdam beatae corporis veritatis
          velit fuga voluptate recusandae!
        </p>
        <ul>
          <li>
            <NuxtLink to="/servicos/desenvolvimento">Desenvolvimento</NuxtLink>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
import BarraMenu from "@/components/BarraMenu.vue";
export default {
  name: "Servicos",
  components: {
    BarraMenu,
  },
};
</script>

<style>
</style>