<template>
  <div class="container__tentou__solucao">
    <p>Você tentou alguma solução de problemas? (ex: Reiniciar, Reinstalar)</p>
    <div class="container__selecao">
      <q-radio color="purple-12" v-model="text" val="sim" label="Sim" />
      <q-radio color="purple-12" v-model="text" val="nao" label="Não" />
    </div>
  </div>
</template>

<script>
import { ref } from 'vue'

export default {
  setup () {
    return {
      text: ref('')
    }
  }
}
</script>
