<script>
import BlocoNovo from "@/components/BlocoNovo.vue";

export default {
  data() {
    return {
      nomes2: ["Mariana", "Ariane"],
    };
  },
  components: { BlocoNovo  },
};
</script>
<template>
  <main id="content">
    <BlocoNovo id="a" :nomes="['Amanda', 'Antonia']" />

    <BlocoNovo id="b" class="alerta" titulo="Alunos" :nomes="nomes2"/>

    <BlocoNovo id="c" />

    <BlocoNovo id="d" />

    <BlocoNovo id="e" />

    <BlocoNovo id="f" />

  </main>
</template>