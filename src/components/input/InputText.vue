<template>
  <div class="container__input">
    <q-input class="input input__name" color="purple-12" v-model="text" filled type="name" hint="Nome" :rules="[val => !!val || 'Obrigatório']" />
    <q-input class="input input__lastname" color="purple-12" v-model="name" filled type="name" hint="Sobrenome"
    :rules="[val => !!val || 'Obrigatório']" />
  </div>
</template>

<script>
import { ref } from 'vue'

export default {
  setup () {
    return {
      text: ref(''),
      name: ref('')
    }
  }
}
</script>
