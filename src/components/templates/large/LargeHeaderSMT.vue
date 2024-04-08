<script setup>

</script>
<template>
  <header>
    <div class="top">
      <div class="logo">
        <img src="@/assets/logoSMT.png" alt="logo" />
        <h1>SMT</h1>
      </div>
    </div>
    <div class="bottom">
      <h1>

        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laborum doloremque,
        molestias nobis consequuntur maiores tempora quos! Perspiciatis provident sunt,
        non, vel quasi ex ad quis, accusantium quas recusandae quidem a?
      </h1>
    </div>
  </header>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Lakki+Reddy&display=swap"
    rel="stylesheet"
  />
</template>
<style scoped>
.logo {
  align-items: start;
  display: flex;
}
.logo img {
  width: 7vh;
  margin-right: 15px;
}
.logo h1 {
  font-size: 6vh;
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
  background-color: blueviolet;
}
@import url("https://fonts.googleapis.com/css2?family=Lakki+Reddy&display=swap");
</style>
