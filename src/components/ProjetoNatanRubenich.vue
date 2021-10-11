<!-- Site desenvolvido pelo Discente Natan Evangelista Rubenich -->
<!--Disciplina Tópicos especias em computação aplicada -->

<template>
  <div class="ProjetoNatanRubenich">
    <h1>{{ msg }}</h1>
    <p>
      Projeto desenvolvido para a primeira avaliação referente a disciplina de Tópicos Especiais em Computação Aplicada, ministrada pelo professor Dr. Ivan Pires. Projeto desenvolvido pelo aluno Natan Evangelista Rubenich.  
    </p>
    <h3>O que é o Vue.js ?</h3>
    <p>
    <a href="https://br.vuejs.org/v2/guide/index.html#O-que-e-Vue-js">Vue.js</a>
    é um framework open source de Javascript desenvolvido pelo Evan You. Ideal para trabalhar com grandes UIs
    </p> 
    <h3>Estrutura do Vue.js</h3>
    <p>
      Os projetos em Vue são arquitetados sob componentes criados com a sintaxe HTML, CSS e Javascript em um único arquivo .vue.
    </p>
    <img alt="Estrutura" src="./estrutura.png">
    <p>
      Sua renderização é baseada em DOM, o qual se atualiza sob demanda de dados alterados.
    </p>
    <h3>Instalação</h3>
    <p>
      A instalação foi bem simples, houve a necessidade de instalar o node de forma global, foi utilizado o Setup fornecido pelo proprio site oficial do <a href="https://nodejs.org/en/">NODE.js</a>, assim possibilitando utilizar o NPM.
    </p>
    <p>
      Foi utilizado os comandos <strong>npm install -g @vue/cli </strong>para instalar o framework vue.js
    </p>
    <img alt="NPM" id="NPM" src="./npm.png">
    <h3>Criação do Projeto</h3>
    <p>
      A Criação do projeto foi bastante simples, foi usado como referencia o site oficial dos desenvolverores do VUE.js
    </p>
    <img alt="criacao" id="craicao" src="./criacao.png">
    <h3>Extensão</h3>
    <p>
      Foi instalado também uma extensão do navegador Brave chamada <a href="https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=pt-BR">Vue.js devtools</a>, o qual auxilia no desenvolvimento da aplicação pois mostra em detalhes os componenes ta aplicação.
    </p>
    <img alt="extensao" id="extensao" src="./extensao.png">
  </div>
  <!--Talvez não haverá tema de terraplanismo --> 
  
</template>

<script>
export default {
  name: 'ProjetoNatanRubenich',
  props: {
    msg: String
  }
}
</script>

<style scoped>

img {
  max-width: 100%;
  width: 700px;  
}


h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
  <!-- ... talvez ...--> 