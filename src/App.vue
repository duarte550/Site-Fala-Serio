<template>
  <div class="page">
    <navbar class="content"></navbar>
    <destaques></destaques>
    <impacto></impacto>
    <institucional></institucional>
    <saber-mais></saber-mais>
    <rede-social></rede-social>
    <footer-component></footer-component>


  </div>
</template>

<script>
import navbar from './components/navbar.vue';
import destaques from './components/destaques.vue';
import institucional from './components/institucional.vue';
import impacto from './components/impacto.vue';
import saberMais from './components/sabermais.vue';
import footerComponent from './components/footer.vue';
import redeSocial from './components/redesocial.vue';

export default {
  name: 'App',
  components: {
    navbar,
    destaques,
    institucional,
    impacto,
    footerComponent,
    saberMais,
    redeSocial,
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,400;0,700;1,400;1,700&display=swap');
  @font-face {
    font-family: klavikaBold;
    src: url("./assets/klavikaBold.otf");
  }
  .VueCarousel-pagination{
    position:relative;
    top:-50px;
  }
</style>
