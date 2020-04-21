<template>
  <div class="page">
    <navbar class="content"></navbar>
    <destaques></destaques>


  </div>
</template>

<script>

import navbar from './components/navbar.vue';
import destaques from './components/destaques.vue';
export default {
  name: 'App',
  components: {
    navbar,
    destaques
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,400;0,700;1,400;1,700&display=swap');
  @font-face {
    font-family: klavikaBold;
    src: url("./assets/klavikaBold.otf");
  }
  
</style>
