<template>

  <main>
    <div class="main-container">
      <div class="back">
        <img src="../assets/icons/arrow-left-02.svg" alt="icone de voltar">
        <span>Voltar</span>
      </div>
      <h1>Formulário de matrícula</h1>
      <p>
        Preencha os dados abaixo para matricular seu filho na escola de educação
        infantil Estrelas do Amanhã.
      </p>
    </div>
  </main>
  <aside>
    <div class="aside-container">
      <header><img src="../assets/logo.svg" alt="logo estrela do amanhã">
        <h2>Porque cada momento de <span>aprendizado</span> conta</h2>
        <p>Inscreva seu filho em nossa escola e veja-o florescer em um ambiente
          acolhedor, seguro e estimulante.</p>
      </header>
      <img src="../assets/pana.svg" alt= "Ilustação de uma professora com crianças">
    </div>
  </aside>
</template>

<script>
export default {
  name: 'FormMatricula',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style src="./global.css"/>
<style src="./layout.css"/>
