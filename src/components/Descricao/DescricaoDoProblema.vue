// criar uma caixa de texto para descrição do Problema
<template>
  <div class="container__descricao__do__problema">
    <label class="titulo__descricao__problema" for="descricaoProblema">Descrição do Problema:</label>
    <textarea class="descricao__do__problema" id="descricaoProblema" v-model="descricao" rows="4" cols="50"></textarea>
  </div>
</template>

<script>
export default {
  data () {
    return {
      descricao: ''
    }
  }
}
</script>
