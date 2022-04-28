<script>
import MenuLateral from "@/components/MenuLateral.vue";
import BlocoCabecalho from "@/components/BlocoCabecalho.vue"
import BlocoRodape from "@/components/BlocoRodape.vue"
import BlocoPrincipal from "@/components/BlocoPrincipal.vue"
export default {
  components: { MenuLateral, BlocoCabecalho, BlocoRodape, BlocoPrincipal },
};
</script>
<template>
  <MenuLateral />
  <BlocoCabecalho />
  <BlocoPrincipal />
  <BlocoRodape />
</template>
<style></style>
