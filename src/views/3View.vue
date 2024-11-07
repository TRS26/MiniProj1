<template>
  <div class="home">
    <img id="img" alt="Vue logo" src="../assets/eu.png">
      <div>
        <p class="title">Hobbies</p>
        <p class="text">- Ler</p>
        <p class="text">- Jogar</p>
        <p class="text">- Séries</p>
        <p class="text">- Desporto</p>
      </div>
  </div>
</template>

<style scoped>
.home{
  margin: 0;
  font-family: "Itim", cursive; font-weight: 400; font-style: normal;
  display: flex;
  height: 710px;
}
#img{
  width: 620px;
  height: 650px;
  padding: 25px 43px 0px 43px;
  display: flex;
}
.title{
  font-size: 72px;
  margin-left: 370px;
}
.text{
  font-size: 40px;
  text-align: justify;
  margin-left: 100px;
}
</style>