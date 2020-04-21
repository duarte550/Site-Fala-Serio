<template>
    <div class="container-carousel">
        <Carousel autoplay=True perPage=1 paginationPadding=5 paginationActiveColor='#3884c5'>
            <Slide><img src="../assets/FotosParaRolamento/DSC_0370.jpg" alt="" class="slide-photo"></Slide>
            <Slide><img src="../assets/FotosParaRolamento/DSC_0356.jpg" alt="" class="slide-photo"></Slide>
            <Slide><img src="../assets/FotosParaRolamento/DSC01676.jpg" alt="" class="slide-photo"></Slide>
            <Slide><img src="../assets/FotosParaRolamento/DSC01913.jpg" alt="" class="slide-photo"></Slide>
            <Slide><img src="../assets/FotosParaRolamento/DSC02008.jpg" alt="" class="slide-photo"></Slide>
        </Carousel>
    </div>
</template>

<script>

import { Carousel, Slide } from 'vue-carousel';
export default {
  name: 'destaques',
  components: {
    Carousel,
    Slide
  }
}
</script>

<style>
    .container-carousel{
        height: 60vh;
        max-width: 1200px;
        
    }
    .slide-photo{
        height: 60vh;
        width: 100%;
    }
</style>