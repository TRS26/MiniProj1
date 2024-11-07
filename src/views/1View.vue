<template>
  <div class="home">
      <img id="img" alt="Vue logo" src="../assets/eu.png">
      <div>
        <p class="title">Quem sou eu?</p>
        <p class="text">Profissional na área de Comunicação e Multimédia, com
                        experiência como designer e desenvolvedor web. Licenciado
                        Universidade de Trás-os-Montes e Alto Douro em 2022,
                        especializado em desenvolvimento web, com destaque para PHP e
                        React. Possuo experiência em estágios nas áreas de design e
                        desenvolvimento web, em empresas como Média Byter, Atipico
                        Design e Purple Profile.</p>
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
  margin-right: 20px;
}
</style>