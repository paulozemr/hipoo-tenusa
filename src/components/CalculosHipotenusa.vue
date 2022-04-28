<script></script>
<template>
  <aside>
    <input id="Adja" type="number" placeholder="Adjacente" />
    <input id="Oposto" type="number" placeholder="Oposto" />
    <button id="calcular" placeholder="Calcular">Calcular</button>
    <input id="resposta" placeholder="Resposta da Hipotenusa" />
  </aside>
</template>
<style>
aside {
  background: #da4453; /* fallback for old browsers */
  background: -webkit-linear-gradient(
    to right,
    #89216b,
    #da4453
  ); /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(
    to right,
    #89216b,
    #da4453
  ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

#Adja {
  padding-left: 20px;
  margin: 50px;
  border-radius: 1px;
  border-color: blue;
  height: 50px;
}
#Oposto {
  padding-left: 20px;
  margin: 50px;
  border-radius: 2px;
  border-color: red;
  height: 50px;
}
#calcular {
  padding-left: 10px;
  height: 120px;
  width: 120px;
  margin: 60px;
  margin-left: 80px;
  margin-top: 20px;
  border-radius: 60px;
  border-color: white;
  background-image: radial-gradient(
    circle at 50% 50%,
    #e942bd 0,
    #f238ad 8.33%,
    #fa309c 16.67%,
    #fe2c8a 25%,
    #ff2c79 33.33%,
    #ff3069 41.67%,
    #ff3858 50%,
    #fb4148 58.33%,
    #f54b37 66.67%,
    #ee5526 75%,
    #e55e10 83.33%,
    #db6700 91.67%,
    #d07000 100%
  );
}
#resposta {
  padding-bottom: 100px;
  padding-left: 20px;
  margin-left: 35px;
  margin-bottom: 75px;
  border-width: 10px;
  display: flex;
  justify-content: center;
  border-color: purple;
}
</style>
