<template>
  <div class="home">
      <img id="img" alt="Vue logo" src="../assets/eu.png">
      <div>
        <p class="title">O que faço?</p>
        <p class="text">Estou neste momento no segundo ano do mestrado de Tecnologias multimédia, mas ao mesmo tempo trabalho em part-time no continente onde trabalho como charcuteiro. </p>
      </div>
  </div>
</template>

<style scoped>
.home{
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
  margin-right: 20px;
}
</style>