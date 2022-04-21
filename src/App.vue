<script>
import MenuLateral from "@/components/MenuLateral.vue";
import Cabecalho from "./components/Cabecalho.vue";
import Rodape from "./components/rodape.vue";
import BlocoPrincp from "./components/BlocoPrincp.vue";

export default {
  components: { MenuLateral, Cabecalho, Rodape, BlocoPrincp },
};
</script>
<template>
  <MenuLateral />
  <Cabecalho />
  <BlocoPrincp />
  <Rodape />
</template>
<style></style>
