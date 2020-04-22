<template>
  <div class="page">
    <navbar class="content"></navbar>
    <destaques></destaques>
    <video-institucional></video-institucional>


  </div>
</template>

<script>

import navbar from './components/navbar.vue';
import destaques from './components/destaques.vue';
import faixa2 from './components/faixa2.vue';

export default {
  name: 'App',
  components: {
    navbar,
    destaques,
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
