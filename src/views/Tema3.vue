<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Documentación y registros

    .row.justify-content-center
      .col-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-left")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img1.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 La toma y registro de la información generada en la unidad productiva, garantiza contar con un historial de todos los eventos ocurridos, permitiendo la recolección de datos y el análisis de información que se traduce en un constante mejoramiento de la sanidad, inocuidad y producción de la finca (Tafur y Nieto, 2011). Algunos de estos eventos pueden ser: vacunación, desparasitación, lavado y desinfección de instalaciones, lavado y desinfección de utensilios y elementos de la producción, análisis y calidad de agua, utilización de medicamentos veterinarios e insumos agropecuarios, mantenimiento de equipos de la granja, entrada y salida del personal a la granja.

    p(data-aos="zoom-in").mt-5 A continuación, se invita a ver una presentación para profundizar sobre el tema1:

    .tarjeta.p-4(style="background-color: #EBE1BF").mb-5(data-aos="fade-left").mt-5
      SlyderA(tipo="b")
        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            p Para hacer la implementación de las buenas prácticas ganaderas en la producción porcina, es necesario conocer los registros, documentos y formatos necesarios para hacer la ejecución de dicho plan.
          
          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema3/img2.png', alt='')

        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            p En ese sentido se tienen registros de entrada y salida de vehículos, personas y animales al predio productivo. Además, el registro de medicamentos veterinarios utilizados dentro de la producción y el inventario de insumos agropecuarios.

          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema3/img3.png', alt='')

          
        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            p También se tiene el registro de las labores y procedimientos de limpieza y desinfección de las instalaciones, utensilios y elementos que son necesarios dentro de la producción. Así mismo, el registro de manejo integral de residuos sólidos y líquidos, y el control de plagas y roedores, entre otros.

          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema3/img4.png', alt='')

        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            p Por parte de documentos externos se tiene la inscripción del predio en planeación para legalizar el uso del suelo con fines agropecuarios, además la inscripción del predio para registro sanitario ante el ICA, igualmente, la certificación de zona libre de peste porcina (PPC) o Registro Único de vacunación.
          
          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema3/img5.png', alt='')

        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            p De esta misma forma se tiene punto de concesión de agua, que debe ser legalizado por la Corporación Autónoma Regional (CAR), y además una constancia del profesional médico veterinario.

          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema3/img6.png', alt='')

          
        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            p Estos documentos son básicos e importantes para el proceso de certificación para las buenas prácticas ganaderas en la producción porcina.

          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema3/img7.png', alt='')

    .row.justify-content-center.mt-5
      .col-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-left")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img8.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 De igual forma, debe existir un registro individual para cada animal, donde se escriban todos los procedimientos realizados durante la estancia en la finca (eventos sanitarios, reproductivos, desempeño productivo, procedimientos quirúrgicos y con sus respectivos tratamientos). Archivar la guía sanitaria de movilización del ICA (original y copia), de todos los animales que ingresan a la granja.

    p(data-aos="zoom-in").mt-5 El productor que desee certificarse en BPG en la producción porcina, deberá tener en regla la siguiente documentación:

    .row.justify-content-center.mt-5
      .col-5
        .tarjeta-tema1.color-acento-botones.p-4
          p • Certificado de uso del suelo.
          p • Guía de movilización interna.
          p • Registro sanitario del predio.
          p • Registro único de identificación en zona libre de PPC.
          p • Registro único de vacunación en zona endémica.
          p • Constancia registro de predio ante el ICA.
          p • Constancia expedida por el médico veterinario.
          p • Legalización del recurso hídrico.
          p • Soportes gestión del manejo de residuos líquidos. 
          p • Guías de movilización animal.

    .row.mt-5(data-aos="fade-right")
      .col
        .tarjeta-tema1.color-acento-contenido.p-4
          p <b>Nota:</b> es necesario revisar la normatividad vigente de las BPG, establecida por el Instituto Colombiano Agropecuario - ICA y, finalmente, aplicar la lista de chequeo de “Predios productores de leche con destino al consumo humano – Forma 3- 519”. Esta lista de chequeo se aplica para encontrar carencias ante la normatividad e iniciar un plan que permita completar los aspectos faltantes para poder obtener la certificación.

    p(data-aos="zoom-in").mt-5 Se sugiere revisar la lista de chequeo para predios productores de leche con destino al consumo humano – Forma 3- 519

    separador
    #t_3_1.titulo-segundo.color-acento-contenido
      h2 3.1 Tipo, formatos y diligenciamiento

    p(data-aos="zoom-in") Existen varios tipos de formatos o registros que deben llevarse dentro de la producción, ya sea interna o externamente, los cuales son de gran importancia para consignar la información relevante del proceso productivo y que, además, puede apoyar la toma de decisiones en la unidad productiva, entre ellos  figuran los de registros de entrada y salida del predio, limpieza y desinfección, aplicación de medicamentos, capacitaciones del personal, vacunación y desparasitación, reproducción, parámetros productivos, entre otros.

    .row.justify-content-center.mt-5
      .col-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-left")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img9.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Estos formatos deben ser diligenciados consignando la información precisa, veraz y relevante de los diferentes procesos, procedimientos y actividades que se llevan en cada una de las áreas de la unidad productiva, por el personal responsable, no debe tener tachones ni enmendaduras, llevarse de manera organizada y secuencial para que tenga un orden lógico y pueda servir tanto de soporte como constancia de cada una de las actividades que se desarrollan dentro del predio y que serán solicitados efectivamente por el personal del ICA como requisito para otorgar la certificación.

    p(data-aos="zoom-in").mt-5 A continuación, se ilustran algunos de los formatos más relevantes en la implementación de las BPG en la producción porcina, los cuales le permiten al productor hacer seguimientos y control de los procesos que se llevan a cabo en la unidad productiva.

    .row.justify-content-center.mt-5
      .col-10
        .tarjeta(style="background-color: #3981C8").p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/curso/temas/tema3/img10.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1.text-white Formatos para registro en la implementación de BPG en la producción porcina

                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/CF02_3.1_Formatos _para_ registro_en_la_implementación_de_BPG_en la_producción_porcina.pptx')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    separador
    #t_3_2.titulo-segundo.color-acento-contenido
      h2 3.2 Trámite

    .row.justify-content-center
      .col-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-left")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img11.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 La tramitación de los documentos necesarios para realizar la implementación de las buenas prácticas ganaderas en la producción porcina, son de carácter estatal, en su mayoría expedidas por el Instituto Colombiano Agropecuario - ICA, a los que se puede acceder ya sea a través de plataforma o de forma presencial. Algunos de los procesos o actividades que se realizan para ser certificadas requieren de una planeación y seguimiento, por lo cual debe planificarse y ejecutarse meticulosamente para que se lleven con éxito, entre estas labores se tienen:

    .row.mt-5
      .col-6
         ImagenInfografica.color-primario
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/temas/tema3/img12.svg', alt='')

          .tarjeta.color-acento-contenido--borde.p-3(x="41.7%" y="4.5%" numero="+")
            .h5.mb-2 Registros y formatos utilizados internamente
            p Sirven como soporte de los procedimientos, procesos y actividades llevadas a cabo dentro de la unidad productiva, estos solo deben diligenciarse de forma correcta e interpretarse y archivarse para tenerlos en cuenta en cualquier momento, ya sea para consultar o tomar decisiones acerca de la producción.

          .tarjeta.color-acento-contenido--borde.p-3(x="61%" y="48.8%" numero="+")
            .h5.mb-2 Solicitud de certificación
            p En cualquier punto de atención del ICA, ya sea de manera virtual, telefónica o presencial, en cualquier fecha y sin ningún costo, se debe generar una visita de verificación por parte de un profesional de la institución quien ejerce su papel como auditor del proceso, luego se llevará a cabo la inspección y evaluación del predio productivo a certificar.

          .tarjeta.color-acento-contenido--borde.p-3(x="43%" y="95.5%" numero="+")
            .h5.mb-2 Tiempo de espera
            p Este consiste en que se resuelvan las fallas o incongruencias en la implementación del plan de BPG en la producción o se procede a certificar el predio; en el primer caso se programa una nueva visita de validación de las acciones implementadas y en el segundo se otorga la certificación a la producción el cual puede tardar  más o menos 30 días.
</template>

<script>
export default {
  name: 'Tema3',
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
