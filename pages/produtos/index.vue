<template>
  <div>
    <div class="bg-gray-100">
      <BarraMenu />
    </div>
    <div class="conteiner">
      Produtos
      <p>
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Labore
        possimus iste aliquid illum asperiores repellat tempora id, neque magnam
        similique blanditiis perspiciatis, optio rem, ipsum non architecto a.
        Doloremque, veritatis. Lorem, ipsum dolor sit amet consectetur
        adipisicing elit. Quas beatae fuga recusandae atque ducimus, sapiente
        delectus magni adipisci iste temporibus vitae magnam labore omnis
        dolore, eveniet consectetur, sunt quisquam deleniti. Lorem ipsum dolor
        sit amet consectetur adipisicing elit. Voluptatum natus aliquam
        quisquam, dolore vel aut rerum quos iusto accusantium pariatur a ut ad.
        Dolorum fugit numquam illum dignissimos, quod ipsa.
      </p>
      <NuxtLink to="/produtos/produto-a">Produto A</NuxtLink>
    </div>
  </div>
</template>

<script>
import BarraMenu from "@/components/BarraMenu";
export default {
  name: "Produtos",
  components: {
    BarraMenu,
  },
};
</script>

<style>
</style>