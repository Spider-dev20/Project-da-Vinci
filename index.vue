<template>
<body>
  <div>
    <link rel="stylesheet" href="~/components/index">
    <h1>LEONARDO DA VINCI RESTAURANTE</h1>
    <h1>FOOD IS ART</h1>
    <h1><nuxt-link to="./about">Menu</nuxt-link></h1>
    <img src="./Leonardo.jpg" alt="">
    <button onclick="document.get"></button>
  </div>
</body>
</template>

<script>
export default {
  name:"index" 
}
</script>
<style>
  body {
    background-color: burlywood;
    text-align: center;
  }
  h1 {
    font-family: initial;
    border: 15px solid brown;
    background-color: brown;
    margin-block: 30px;
  }
  a {
    color: black;
  }
</style>