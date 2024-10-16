<template>
  <div class="sistema">
    <q-select class="sistema__operacional" color="purple-12" v-model="model" :options="options" :rules="[val => !!val || 'Obrigatório']">Sistema Operacional</q-select>
  </div>
</template>

<script>
import { ref } from 'vue'

export default {
  setup () {
    return {
      model: ref(null),

      options: [
        'Windows', 'macOS', 'Linux', 'Outro'
      ]
    }
  }
}
</script>
