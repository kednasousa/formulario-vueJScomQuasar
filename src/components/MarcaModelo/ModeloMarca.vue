<template>
  <div class="container__modelo_marca">
    <q-input class="input modelo__marca" color="purple-12" v-model="text" filled type="modeloMarca" hint="Modelo Marca" :rules="[val => !!val || 'Obrigatório']" />

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
