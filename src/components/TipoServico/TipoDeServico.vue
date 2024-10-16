<template>
  <div class="tipo__de__servico">
    <q-select class="input__servico" color="purple-12" v-model="model" :options="options" :rules="[val => !!val || 'Obrigatório']">Tipo de Serviço</q-select>
  </div>
</template>

<script>
import { ref } from 'vue'

export default {
  setup () {
    return {
      model: ref(null),

      options: [
        'Problema de Hardware', 'Problema de Software', 'Problema de Rede', 'Outro'
      ]
    }
  }
}
</script>
