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

      <form>
        <fieldset>
          <legend>Informações da Criança</legend>
          <div class="input-wrapper">
            <label for="fullname">Nome completo</label>
            <input type="text" name="fullname" id="fullname"
                   placeholder="Qual nome da criança">
          </div>
          <div class="input-wrapper">
            <label for="birth">Data de nascimento</label>
            <input type="date" name="birth" id="birth" lang="pt-BR">
          </div>
          <div class="select-wrapper">
            <label for="gender">Sexo</label>
            <select name="gender" id="gender">
              <option value="female">Feminino</option>
              <option value="male">Masculino</option>
              <option value="na">Prefiro não responder</option>
            </select>
          </div>
          <div class="textarea-wrapper">
            <label for="medical-info">Informações médicas</label>
            <textarea name="medical-info" id="medical-info" cols="30" rows="10"
                      placeholder="A criança possui alguma condição médica que a escola deve estar ciente? (Se sim, especifique)"></textarea>
          </div>

          <div class="droparea-wrapper">
            <input type="file" id="birth-file" name="birth-file">
            <img src="../assets/icons/cloud-upload.svg" alt="">
            <p>Clique aqui para selecionar os arquivos</p>
          </div>
        </fieldset>
      </form>

    </div>
  </main>
  <aside>
    <div class="aside-container">
      <header><img src="../assets/logo.svg" alt="logo estrela do amanhã">
        <h2>Porque cada momento de <span>aprendizado</span> conta</h2>
        <p>Inscreva seu filho em nossa escola e veja-o florescer em um ambiente
          acolhedor, seguro e estimulante.</p>
      </header>
      <img src="../assets/pana.svg" alt="Ilustação de uma professora com crianças">
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
