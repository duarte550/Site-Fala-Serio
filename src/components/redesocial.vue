<template>
  <div class="container-redesocial">
      <div class="texto-rede-social">
        <h1>QUALQUER COISA... FALE COM A GENTE!</h1>
        <div class="linha-rede-social"><img src="../assets/Facebook.png" alt="" class="img-rede-social"><p>/iniciativafalaserio</p></div>
        <div class="linha-rede-social"><img src="../assets/Instagram.png" alt="" class="img-rede-social"><p>@iniciativafalaserio</p></div>
        <div class="linha-rede-social"><img src="../assets/whatsapp.png" alt="" class="img-rede-social"><p>(11)9 8859-6980</p></div>
        <div class="linha-rede-social"><img src="../assets/e-mail-envelope.png" alt="" class="img-rede-social"><p>iniciativafalaserio@gmail.com</p></div>
      </div>
  </div>
</template>

<script>


export default {
  name: 'redesocial',
  
}
</script>

<style>
    .container-redesocial{
        height:50vh;
        background-color: #f5f5dc;
        max-width: 1200px;
        padding-top: 0.5%;
        font-family: klavikaBold, sans-serif, bold;
        text-align: left;
        align-items: center;
        color: #3884c5;
        margin-top: 0;
        font-size: 1.2em;
    }
    .texto-rede-social{
        padding-left: 5%;
        padding-top: 2%;
    }
    .linha-rede-social{
        font-size: 1.8em;
        display: flex;
        flex-direction: row;
        align-items: center;

    }
    .img-rede-social{
        height: 70px;
        width: 70px;
        padding-right: 20px;
        padding-bottom: 20px;
    }
</style>