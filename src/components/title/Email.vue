<template>
  <q-input class="input email" color="purple-12" v-model="email" filled type="email" hint="Email" :rules="[val => !!val || 'Obrigatório']" />
</template>

<script>
export default {
  name: 'EmailFormulario'
}
</script>
