<template>
  <div class="container-saber-mais">
    <div class="saber-mais-alinhamento-texto">
      <h1>PARA SABER MAIS</h1>
      <p>Uma coleção <span class="texto-azul">única</span> de material sobre diversos <span class="texto-azul">cursos</span> e detalhes da <span class="texto-azul">vida acadêmica</span>
        feita por alunos da <span class="texto-azul">USP</span>.
      </p>
      <a href="" id="link-ler-mais-institucional">
        <div class="ler-mais ler-mais-saber-mais">
            <p class="p-ler-mais">Ler mais</p>
            <font-awesome-icon icon="angle-double-right" />
            
        </div>
      </a>
  </div>
  </div>
</template>

<script>


export default {
  name: 'saberMais',
  
}
</script>

<style>
    .container-saber-mais{
        position: relative;
        background-image: url("../assets/regi.png");
        height: 60vh;
        max-width: 1200px;
        background-size: cover;
        color:white;
        text-align: right;
        justify-content: right;
        font-family: klavikaBold, sans-serif, bold;
        font-size: 1.8em;
        
    }

    .texto-azul{
      color:#3884c5;
    }
    .saber-mais-alinhamento-texto{
      position: absolute;
      width: 40%;
      right: 5%;

      top:5%;

      
      
    }
    h1{
      color:#092949;
    }
    p,h1{
      margin: 0;
      
    }
    .ler-mais{
      position: relative;
      right:5%;
      padding-top: 2%;
      color:#092949;
    }
    .ler-mais-saber-mais{
      left:45%; 
    }
    
</style>