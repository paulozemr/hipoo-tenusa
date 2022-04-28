<script>
import CalculosHipotenusa from "@/components/CalculosHipotenusa.vue";
import CAbeça from "@/components/CAbeça.vue"
export default {
  components: { CalculosHipotenusa , CAbeça },
};
</script>
<template>
  <CAbeça />
  <CalculosHipotenusa />
  <main id="content">Desenho do triangulo-retangulo</main>
  <footer id="footer"></footer>
</template>
