<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.justify-content-center 
      .col-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-left")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/img1.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            h4 Implementación BPG en producción porcina
            br
            br
            p.mb-0 Formular, diseñar y ejecutar un plan de implementación en BPG en la producción pecuaria, necesita no solo del conocimiento de la normativa y los requerimientos de la misma, sino de conocer a fondo la unidad productiva con la que se está trabajando, para saber cuáles son sus puntos fuertes y sus debilidades a nivel de infraestructura, procedimientos, procesos productivos, personal, documentos, entre otros. Por esta razón, el proceso de BPG es una vinculación directa de la producción pecuaria con la calidad, sanidad, inocuidad y trazabilidad de los productos de origen animal de dichas unidades productivas. 

    p(data-aos="fade-right").mb-5.mt-5 Partiendo de lo anterior, se da la bienvenida al estudio de este componente formativo y, para comenzar, se invita a explorar el video que se presenta a continuación: 
      figure
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
            figcaption Video: Leyenda del video
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
