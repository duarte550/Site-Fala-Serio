<template>
  <div class="container-footer">
      <img src="../assets/logo_branco.png" alt="" style="height:100%">
      <div class="texto-footer">
            <p>Iniciativa Fala Sério © 2020</p>
            <p>Não sendo para fins comerciais ou políticos, todo o conteúdo deste portal pode ser compartilhado
                ,copiado e distribuído, desde que citado autoral e a fonte.
            </p>
            
      </div>
      
      
  </div>
</template>

<script>


export default {
  name: 'footer',
  
}
</script>

<style>
    .container-footer{
        background-color:#9fcf67;
        height: 10vh;
        max-width: 1200px;
        display: flex;
        flex-direction: row;
        align-items: center;
        color: white;
        
    }
    .texto-footer{
        width:45%;
        text-align: start;
    }
</style>