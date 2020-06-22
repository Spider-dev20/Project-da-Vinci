<template>
    <div>
    <h1 class="menu">Menu</h1>
    <h1><nuxt-link to="/">Home Page </nuxt-link></h1>
    <img src="./pizza.jpg" alt="Pizza Margherita" >
    <h2>Pizza Magherita</h2>
    <img src="./pasta.jpg" alt="Italien Pasta">
    <h2>Pasta de Italia</h2> 
    <img src="./crep.jpg" alt="Crepe">
    <h2>Crepe</h2>

    
    </div>
</template>

<script>
export default {
    name:"about"
}
</script>
<style>
.menu{
        font-size: 45px;
        color:black;
    }

image{
width: 500px; 
height:400px;
     
}
</style>