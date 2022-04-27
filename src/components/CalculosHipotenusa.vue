<script></script>
<template>
  <aside>
    <input id="Adja" type="number" placeholder="Adjacente" />
    <input id="Oposto" type="number" placeholder="Oposto" />
    <button id="calcular" placeholder="Calcular"></button>
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
  padding-left: 10px;
  margin: 10px;
  border-radius: 1px;
  border-color: blue;
}
#Oposto {
  padding-left: 10px;
  margin: 10px;
  border-radius: 2px;
  border-color: red;
}
#calcular {
  padding-left: 10px;
  height: 25px;
  width: 25px;
  margin: 10px;
}
</style>
