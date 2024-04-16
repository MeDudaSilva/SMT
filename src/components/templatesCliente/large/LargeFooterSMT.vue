<script setup></script>

<template>
  <footer>
    <div id="footer">
      <ul id="conheca">
        <h1>Conheça-nos</h1>
        <li>Sobre</li>
        <li>Comunidade</li>
        <li>Acessibilidade</li>
      </ul>
      <ul id="suporte">
        <h1>Suporte</h1>
        <li>Perguntas</li>
        <li>Problemas</li>
        <li>Ajuda</li>
      </ul>

      <ul id="termos">
        <h1>Termos</h1>
        <li>Politica de privacidade</li>
        <li>Termos de uso</li>
        <li>Cookies</li>
      </ul>
    </div>
    <div id="smt">
      <div>
        <p>©SistemaMultTrabalhista, SMT</p>
      </div>
    </div>
  </footer>
</template>
<style scoped>

#smt {
  display: flex;
  justify-content: center;
  width: 100%;
}

#smt div {
  width: 50%;
  border-top: 0.3vh solid white;
  display: flex;
  justify-content: center;
  font-size: 2vh;
}

#footer {
  display: flex;
  justify-content: space-around;
  height: 20vh;
  padding-top: 3vh;
}

footer {
  background: rgb(41, 42, 44);
  color: white;
  width: 100%;
}

li {
  list-style: none;
  font-size: 2vh;
}
h1 {
  font-size: 3vh;
}
</style>
