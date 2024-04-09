<script setup>
import Menu from "vue-material-design-icons/Menu.vue";
</script>
<template>
  <header>
    <div class="top">
      <div class="logo">
        <img src="@/assets/SMTlogo.ico" alt="logo" />
        <h1>SMT</h1>
      </div>
      <div class="barra-pesquisa">
        <input
          size="100"
          type="text"
          v-model="search"
          id="barra-pesquisa"
          placeholder="Procurar servisos"
        />
      </div>
      <div class="user"><img src="/public/Darth-Vader-Star-Wars-PNG.png" alt="" /></div>
    </div>
    <div class="bottom">
      <Menu size="7vh" />
      <p>Ranking</p>
    </div>
  </header>
</template>
<style scoped>
#barra-pesquisa {
  width: 600px;
  height: 45px;
  border-radius: 30px;
  font-size: 22px;
  padding: 0px 15px;
  margin: 3vh 50vh;
  text-align: center;
  border: 3px solid blue;
  box-shadow: 0 10px 30px 0 black;
}
.user img {
  width: 8vh;
  display: flex;
  margin-left: 10vh;
}
.logo {
  align-items: start;
  display: flex;
}
.logo img {
  width: 10vh;
  margin-right: 15px;
}
.logo h1 {
  font-size: 8vh;
  font-family: "Lakki Reddy", serif;
  color: black;
}
header {
  display: flex;
  flex-direction: column;
}
.top {
  display: flex;
  padding: 10px;
  height: 9vh;
  flex-direction: row;
}
.bottom {
  display: flex;
  flex-direction: row;
  background-color: rgb(192, 192, 192);
  margin-top: 2vh;
}
  p{
    font-family: "Lakki Reddy", serif;
    font-size: 30px;
    text-align: center;
    padding: 2vh 0 0 2vh;
  }
@import url("https://fonts.googleapis.com/css2?family=Lakki+Reddy&display=swap");
</style>
