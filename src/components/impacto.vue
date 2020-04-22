<template>
  <div class="container-impacto">
      <h1>IMPACTO DO FALA SÉRIO</h1>
      <div class="flex-impacto">
          <div class="coluna-impacto"><img src="../assets/book_branco.png" alt="" class="img-impacto"><p class="numero-impacto">1563</p><p class="texto-impacto">alunos impactados</p></div>
          <div class="coluna-impacto"><img src="../assets/school_branca.png" alt="" class="img-impacto"><p class="numero-impacto">15</p><p class="texto-impacto">escolas visitadas</p></div>
          <div class="coluna-impacto"><img src="../assets/clock_branco.png" alt="" class="img-impacto"><p class="numero-impacto">6</p><p class="texto-impacto">anos de projeto</p></div>
      </div>
  </div>
</template>

<script>


export default {
  name: 'impacto',
  
}
</script>

<style>
    .container-impacto{
        height:50vh;
        background-color: #9fcf67;
        max-width: 1200px;
        padding-top: 0.5%;
        font-family: klavikaBold, sans-serif, bold;
        text-align: center;
        align-items: center;
        color: white;
        margin-top: 0;
    }
    .flex-impacto{
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center;
    }
    .img-impacto{
        width: 45%;
    }
    .numero-impacto{
        font-size: 5em;
    }
    .texto-impacto{
        font-size: 2em;
    }
    p{
        margin-top:0;
        margin-bottom:0;
    }
</style>