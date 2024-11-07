<template>
  <div class="home">
      <img id="img" alt="Vue logo" src="../assets/eu.png">
      <div>
        <p class="title">O que faço?</p>
        <p class="text">Estudante de mestrado na Universidade de Trás os montes e alto
                        douro, onde estou a realizar o mestrado em Tecnologias
                        Multimédia.</p>
        <img id="cv" src="../assets/CV.png">
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
#cv{
  width: 300px;
  height: 300px;
  padding: 0px 43px 0px 400px;
  display: flex;
}
.title{
  font-size: 72px; 
  margin-left: 370px;
}
.text{
  font-size: 40px;
  text-align: justify;
  margin-right: 20px;
}
</style>