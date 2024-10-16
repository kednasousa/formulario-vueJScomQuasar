<template>
  <q-input class="input input__phone" color="purple-12" v-model="phone" filled type="tel" hint="Telefone" mask="## # ####-####" fill-mask
  :rules="[val => !!val || 'Obrigatório']" />
</template>

<script>
export default {
  data () {
    return {
      phone: ''
    }
  }
}
</script>
