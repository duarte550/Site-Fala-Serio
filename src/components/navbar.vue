<template>
  <div class="container">
      <a href=""><img src="../assets/logo.png" alt="logo" style="height:20vh"></a>
      <a href="" class="texto-navbar" style="color:#9fcf67">Home</a>
      <a href="" class="texto-navbar">Quem somos?</a>
      <a href="" class="texto-navbar">Para Saber Mais</a>
      <a href="" class="texto-navbar">Fale conosco</a>
      <button>Contribua!</button>
  </div>
</template>

<script>


export default {
  name: 'navbar',
  
}
</script>

<style>
    .container{
        display: flex;
        flex-direction: row;
        justify-content: space-evenly;
        align-items: center;
        max-width: 1200px;
        width:100%;
        height: 15vh;
        background-color: #f5f5dc;
        font-family: klavikaBold, sans-serif, bold;

    }
    .texto-navbar{
        text-decoration: none;
        color: black;
        font-size: 1.2em;
        transition: text-decoration;
        transition-delay: 0.5s;
        

    }
    .texto-navbar:hover{
        text-decoration: underline;
        opacity: 80%;
    }
    button{
        cursor: pointer;
        background-color:#9fcf67;
        font-family: klavikaBold, sans-serif;
        color: white;
        height: 6vh;
        font-size: 1.2em;
        border-radius: 15px;
        text-align: center;
        padding-left: 20px;
        padding-right: 20px;
        box-shadow: none;
        transition: box-shadow 0.5s;

    }
    button:hover{
        box-shadow: 5px 8px 8px #888888;
        opacity: 80%;
    }
</style>