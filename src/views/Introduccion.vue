<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido(data-aos="zoom-in-left")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p(data-aos="fade-down") El estudio del componente #[b «Plan de promotoría y medios de divulgación»] comienza con la visualización del siguiente video, que de forma genérica explica en qué consiste el plan de promotoría y su importancia. 

    h5(data-aos="fade-down").mb-5 ¡Adelante!
    
    .row.justify-content-center.align-items-center.mb-5           
      .col-lg-12(data-aos="fade-left")     
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/MPcYrgxmS6Y?si=gURqS4gjdxktmLAH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)   
          figcaption Video. Plan de promotoría y medios de divulgación

    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
