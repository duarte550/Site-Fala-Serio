<template>
  <div class="container-video">
      <div class="quem-somos">
        <h1 class="titulo-quem">QUEM SOMOS?</h1>
        <div class="flex-video-texto">
                <iframe class="video-institucional" width="560" height="315" src="https://www.youtube.com/embed/Q0TAsJUlvfA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                <div class="container-texto-video">
                    <div class="texto-video">
                        <p class="texto-institucional">Atuamos para <span class="texto-verde">motivar</span>,<span class="texto-verde"> inspirar</span>, 
                            promover <span class="texto-verde"> autoconhecimento </span> 
                            e mostrar o papel da <span class="texto-verde"> educação 
                            </span>na construção dos sonhos
                            e do futuro de alunos do Ensino Médio Público.</p>
                        
                        <a href="" id="link-ler-mais-institucional">
                            <div class="ler-mais">
                                <p class="p-ler-mais">Ler mais</p>
                                <font-awesome-icon icon="angle-double-right" />
                                
                            </div>
                        </a>
                    </div>
                </div>
            </div>
        </div>
      
  </div>
</template>

<script>


export default {
  name: 'institucional',
  
}
</script>

<style>
    .quem-somos{
        margin-left: 5%;
        padding-top: 2%;
        font-family: klavikaBold, sans-serif, bold;
        
        
    }
    .flex-video-texto{
        display: flex;
        flex-direction: row;
        /*justify-content: space-between;*/
        align-items: center;
        position: absolute;

    }
    .texto-video{
        display: flex;
        flex-direction: column;
        align-items: flex-end;
        font-size:1.4em;
        
        
    }
    .ler-mais{
        margin-right: 15px;
        font-size: 1.2em;
        display: flex;
        flex-direction: row;
        align-items: center;
        width:40%;
        justify-content: flex-end;
        
        
    
       
    }
    .p-ler-mais{
        padding-right: 5px;
        
    }


    .container-video{
        height: 60vh;
        max-width: 1200px;
        background-color: #f5f5dc;
        position: relative;
        
    }
    .texto-institucional{
        text-align: center;
        width: 40%;
        height: 60%;
        font-size: 1.5em;
        color: #3884c5;
    }
    .video-institucional{
        width: 40%;
        position: absolute;
        margin-top: 2%;
        
        
    }

    #link-ler-mais-institucional{
        width:40%;
        text-decoration:none;
        text-align: -webkit-right;
    }
    .container-texto-video{
        margin-right: 10%;
        
    }
    .texto-verde{
        color: #9fcf67;
    }
</style>