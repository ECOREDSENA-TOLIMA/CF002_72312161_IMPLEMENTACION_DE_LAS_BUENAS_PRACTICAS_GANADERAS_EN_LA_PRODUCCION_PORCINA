<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Protocolos

    .row.justify-content-center
      .col-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-left")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img1.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Un protocolo es un documento que describe el conjunto de actividades o medidas que deberá ejecutar el personal de la empresa pecuaria para atender una situación específica de la producción. Estas hojas de ruta o protocolos son de suma importancia en la producción pecuaria, pues son aplicados a actividades que se desarrollan en el día a día y permiten tomar decisiones importantes durante un procedimiento o un evento importante.

    separador
    #t_2_1.titulo-segundo.color-acento-contenido
      h2 2.1 Tipos de procedimientos

    .row.justify-content-center
      .col-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-left")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img2.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Existen diferentes maneras de elaborar un protocolo, todas ellas válidas; sin embargo, lo importante es que lleven una secuencia de los procesos y las actividades a ejecutarse dentro de la producción ganadera, por ello se debe tener en cuenta el proceso productivo de una forma organizada y todo lo que ello conlleva, como las instalaciones, los recursos, los elementos, los sistemas, los animales, el personal y los tiempos que deben cumplirse de los mismos. Además, cabe recalcar que quien debe encabezar el diseño de los planes y protocolos de las producciones pecuarias siempre es el médico veterinario o médico veterinario zootecnista, quien debe aportar a un equipo interdisciplinario que será el encargado de planear, ejecutar y monitorear los mismos.

    .row.mt-5(data-aos="fade-right")
      .col
        .tarjeta-tema1.color-acento-contenido.p-4
          p <b>Nota:</b> aunque no existe modelo específico para formular y diseñar un protocolo o plan dirigido a la producción porcina, existen diferentes formas de hacerlo dependiendo del tema y tipo de protocolo.

    p(data-aos="zoom-in").mt-5 Lo realmente importante es el desarrollo de dichos protocolos que, básicamente, deben seguir las siguientes recomendaciones:

    .row.justify-content-center.mt-5
      .col-7
        .tarjeta.color-primario 
          ol.lista-ol.p-5
            li 
              | • Incluir las principales actividades para los procesos productivos.
            li 
              | • Llevar un orden secuencial y lógico de acuerdo con la línea del proceso productivo.
            li 
              | • Ser fácil de entender por cualquier tipo de personal.
            li 
              | • Debe ser divulgado y comunicado con el personal de la producción.
            li 
              | • Debe ser monitoreado y de ser necesario realizar ajustes.
            li 
              | • Debe cumplirse a cabalidad con lo planteado dentro del protocolo.
            li 
              | • Debe estar escrito y ser de fácil acceso para el personal que lo requiera.

    .tarjeta--container.row.mt-5
      .col-md.tarjeta.p-5
        .row.justify-content-center.mb-4
          .col-auto
            figure
              img(src='@/assets/curso/temas/tema2/img3.svg', alt='')
          
        h4.text-center Protocolos en la producción porcina
        p • Limpieza y desinfección del área de maternidad.
        p • Limpieza y desinfección de jaulas vacías.
        p • Limpieza y desinfección del área de gestación.
        p • Limpieza y desinfección del área de preceba.
        p • Limpieza y desinfección del área de ceba.
        p • Limpieza y desinfección de corrales vacíos ceba.
      .col-md.tarjeta.p-5
        .row.justify-content-center.mb-4
          .col-12
            figure
              img(src='@/assets/curso/temas/tema2/img4.svg', alt='')
          
        h4.text-center Protocolos en la producción porcina
        p • Protocolo para el compostaje.
        p • Protocolo para el manejo de residuos y excretas líquidas.
        p • Disposición de la mortalidad. 
        p • Protocolo para realizar necropsias. 
        p • Protocolo control de roedores y aves.
        p • Protocolo control de insectos.
        p • Protocolo desinfección de vehículos. 

      .col-md.tarjeta.p-5
        .row.justify-content-center.mb-4
          .col-auto
            figure
              img(src='@/assets/curso/temas/tema2/img5.png', alt='')
          
        h4.text-center Protocolos en la producción porcina
        p • Ingreso de animales y salida de animales.
        p • Ingreso y almacenamiento de alimentos.
        p • Tratamiento de animales enfermos. 
        p • Aplicación de medicamentos y vacunas.
        p • Cuarentena, inseminación artificial.
        p • Manejo del parto.
        p • Corte de ombligo.
        p • Corte de colmillos.
        p • Corte de cola. 
        p • Colecta de semen. 

    separador
    #t_2_2.titulo-segundo.color-acento-contenido
      h2 2.2. Métodos y técnicas de programación

    .row.justify-content-center
      .col-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-left")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img6.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 La programación de una granja porcina es una herramienta que posibilita organizar los eventos de la granja a partir de los espacios disponibles, el flujo y el inventario de animales. Su importancia radica en que permite mejorar los procesos productivos, optimizar espacios, organizar el uso y la compra de insumos y disminuye los riesgos sanitarios. 
            br
            br
            p Para programar la granja porcina se debe elaborar un listado de los parámetros a medir de acuerdo al tipo de producción que se tenga o quiera proyectar: cría, engorde, ciclo completo o genética (hembras y machos de alto valor genético, puros o híbridos).

    p(data-aos="zoom-in").mt-5 De acuerdo con lo anterior, se muestra en el siguiente recurso los tipos de granja según su propósito:

    .row.mt-5
      .col-4
        .tarjeta(style="background-color:#FFE9A3").p-4
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema2/img7.png', alt='').mb-3

            h4 Cría
            p • Gestación
            p • Lactancia

      .col-4
        .tarjeta(style="background-color:#FFE9A3").p-4
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema2/img8.png', alt='').mb-3

            h4 Engorde
            p • Precebo
            p • Ceba


      .col-4
        .tarjeta(style="background-color:#FFE9A3").p-4
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema2/img9.png', alt='').mb-3

            h4 Ciclo completo
            p • Gestación y lactancia
            p • Precebo y ceba

    p(data-aos="zoom-in").mt-5 A continuación, se mencionan los aspectos más importantes a calcular para el buen funcionamiento y mantenimiento de la granja porcina:

    .tarjeta.p-4(style="background-color: #EBE1BF").mb-5(data-aos="fade-left").mt-5
      SlyderA(tipo="b")
        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            h3 Instalaciones e inventario de animales
            p De acuerdo con el tipo de producción que se tenga proyectado, se debe calcular el espacio que va a ocupar cada grupo de cerdos dependiendo de la etapa en la que se encuentren, por ejemplo, las instalaciones de maternidad, gestación, precebos, destete, levante y ceba, machos reproductores, entre otras. Para lograrlo, es necesario realizar el inventario de animales que se tiene en la granja, determinando la cantidad exacta de cerdos que se tienen en cada una de las áreas, como se muestra a continuación:

          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema2/img10.png', alt='')

        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            h3 Instalaciones e inventario de animales
            p a. Cuarentena y aclimatación: cerdas de reemplazo.
            p b. Servicios: monta e inseminación, machos reproductores, cerdas destetadas y cerdas hasta confirmar gestación.
            p c. Gestación: cerdas de gestación confirmada y hasta unos días antes del parto.
            p d. Parideras: partos y lactancia. 
            p e. Precebos o destete: se tienen los lechones desde el destete hasta la etapa de levante y ceba.

          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema2/img11.png', alt='')

          
        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            h3 El flujo de animales
            p Este hace referencia al movimiento de animales que se realiza en un espacio de tiempo determinado a partir del paso de los cerdos por cada una de las etapas del proceso productivo, teniendo en cuenta el bienestar animal, el tipo de producción y el clima donde se encuentra ubicada la explotación. Algunos aspectos a tener en cuenta son: 
            p a. Cantidad de animales que entran a la granja.
            p b. Animales de parto.
            p c. Cantidad de servicios.
            p d. Lechones nacidos.
            p e. Cantidad de lechones en destete.
            p f. Cantidad de animales vendidos.

          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema2/img12.png', alt='')

    p(data-aos="zoom-in").mt-5 Sin embargo, habrá algunas áreas que no se necesitarán (dependiendo de los objetivos planteados), es decir, si la granja de cerdos es de engorde, algunas áreas de las mencionadas anteriormente no serán necesarias, como por ejemplo las de gestación y parideras, entre otras. Es muy importante conocer cuál será la cantidad de cerdos que se proyecta tener en cada etapa, ya que esto facilitará el diseño y distribución exitosa de las instalaciones.

    .row.mt-5(data-aos="fade-right")
      .col
        .tarjeta-tema1.color-acento-contenido.p-4
          p <b>Nota:</b> vale la pena recordar que habrá eventos que no se realizan en la granja, porque su tipo de producción es diferente, por ejemplo, si la granja solo se dedica a la ceba de cerdos, no se tendrán en cuenta aspectos como la inseminación, gestación, parto y destete de los animales; por lo tanto, su programación será destinada a necesidades distintas que tienen que ver con la venta de animales.

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
