<template>

  <div id="nav">

    <router-link to="/" id="logo-url">

        <img :src="logo" :alt="alt" id="logo">

    </router-link>
    
 
    <router-link to="/">Home</router-link> 
    <router-link to="/cadastro">Cadastro</router-link>
  </div>


</template>


<script>

    export default {
        name: "Navbar",
        props: ["logo", "alt"]  // Logo do Projeto e as imagens
    }


</script>

<style scoped>

  #nav {
    background-color: #3F7FBF;
    padding: 15px 50px;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }

  #nav #logo-url{
    margin: auto;
    margin-left: 0;;
  }

  #logo {
    width: 40px;
    height: 40px;
  }


  #nav a{

    color: #fff;
    text-decoration: none;
    margin: 12px;
    transition: .5s;
    font-size: 20px;
   

  }
  
 #nav a:hover{
   color: red;
   border-bottom: 2px solid red;
 }

</style>
