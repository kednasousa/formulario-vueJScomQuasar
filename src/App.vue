<template>
  <div id="app">
    <div class="main">
      <div class="main__container">
        <TituloFormulario />
        <div class="container">
          <InputText />
          <EmailFormulario />
          <ContatoFormulario />
          <ModeloMarca />
          <div class="container__selecao">
            <TipoDeServico />
            <SistemaOperacional />
          </div>
          <DescricaoDoProblema />
          <TentouAlgumaSolucao />
          <BotaoSubmit />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import TituloFormulario from 'src/components/title/Title.vue'
import InputText from 'src/components/input/InputText.vue'
import EmailFormulario from './components/title/Email.vue'
import ContatoFormulario from './components/Contact/ContatoFormulario.vue'
import TipoDeServico from './components/TipoServico/TipoDeServico.vue'
import SistemaOperacional from './components/Sistema/SistemaOperacional.vue'
import ModeloMarca from './components/MarcaModelo/ModeloMarca.vue'
import DescricaoDoProblema from './components/Descricao/DescricaoDoProblema.vue'
import TentouAlgumaSolucao from './components/TestouSolucao/TentouAlgumaSolucao.vue'
import BotaoSubmit from './components/Button/BotaoSubmit.vue'

export default {
  name: 'App',
  components: {
    TituloFormulario,
    InputText,
    EmailFormulario,
    ContatoFormulario,
    TipoDeServico,
    SistemaOperacional,
    ModeloMarca,
    DescricaoDoProblema,
    TentouAlgumaSolucao,
    BotaoSubmit
  }
}
</script>
