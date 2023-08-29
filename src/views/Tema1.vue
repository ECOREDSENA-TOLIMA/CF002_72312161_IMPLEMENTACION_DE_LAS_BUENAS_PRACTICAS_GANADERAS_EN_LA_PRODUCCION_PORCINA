<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Plan de implementación

    p(data-aos="zoom-in") Cuando se habla del plan de implementación, se está refiriendo a la descripción de los pasos propuestos que debe seguir un equipo de una organización para alcanzar sus objetivos, a través de una estrategia planificada en una línea de tiempo y actividades. Para tener éxito en la ejecución de este plan se deben tener en cuenta los aspectos que se muestran a continuación.

    .row.mt-5
      .col-6
        LineaTiempoD.color-acento-contenido
          .row(numero="1" titulo="Definir objetivos")
            img(src='@/assets/curso/temas/tema1/img2.svg', alt='').mt-5

          .row(numero="2" titulo="Realizar una investigación adecuada")
            img(src='@/assets/curso/temas/tema1/img3.svg', alt='').mt-5
          
          .row(numero="3" titulo="Identificar todos los riesgos")
            img(src='@/assets/curso/temas/tema1/img4.svg', alt='').mt-5

          .row(numero="4" titulo="Programar todos los hitos")
            img(src='@/assets/curso/temas/tema1/img5.svg', alt='').mt-5

          .row(numero="5" titulo="Asignar tareas")
            img(src='@/assets/curso/temas/tema1/img6.svg', alt='').mt-5
          
          .row(numero="6" titulo="Asignar recursos útiles")
            img(src='@/assets/curso/temas/tema1/img7.svg', alt='').mt-5
      .col-6      
        img(src='@/assets/curso/temas/tema1/img1.svg')

    separador
    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1 Componentes  

    p(data-aos="zoom-in") Los componentes que forman parte de la implementación de las BPG en las producciones porcícolas se encuentran establecidos a través de la Resolución 76509 del 2020 del ICA, que explican en detalle la normatividad generada por el Estado colombiano para lograr alcanzar cada uno de los requerimientos en la implementación de las buenas prácticas ganaderas en las unidades productivas. 
    p(data-aos="zoom-in") Los componentes que tiene en cuenta el ICA para la certificación en buenas prácticas ganaderas se agrupan en los siguientes aspectos:

    .tarjeta.p-4(style="background-color: #EBE1BF").mb-5(data-aos="fade-left").mt-5
      SlyderA(tipo="b")
        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            h3 Inscripción de granjas
            p Los predios y el inventario de porcinos de producción deben estar registrados ante el ICA y estar autorizados por el Plan de Ordenamiento Territorial (POT).

          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema1/img8.png', alt='')

        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            h3 Sanidad animal y bioseguridad
            p Los animales deben cumplir con un plan sanitario que incluya la prevención, diagnóstico y manejo de enfermedades de control oficial, endémicas y las demás que pudiere requerir la autoridad sanitaria, también debe incluir prácticas de manejo, planes de vacunación, sobre todo de PPC y desparasitación, tratamientos comúnmente realizados en la producción, plan de emergencias, procedimiento para adquisición de animales y cuarentena.

          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema1/img9.png', alt='')

          
        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            h3 Registros y documentación
            p El registro es la información que se produce en la producción y asegura que se pueda tener un historial con todo lo acontecido para que se pueda tener en cuenta en la toma de decisiones y el mejoramiento en la productividad, sanidad e inocuidad de la producción. Todos los planes y procedimientos que hacen parte del plan de implementación de BPG deben ser registrados y archivados de manera adecuada, junto con cada uno de los formatos que posibilitan esta actividad.

          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema1/img10.png', alt='')

        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            h3 Control de medicamentos y otros insumos
            p Utilizar de forma correcta los medicamentos veterinarios, las vacunas, suplementos, alimentos balanceados, sales mineralizadas, insumos agropecuarios y plaguicidas es de gran importancia en la implementación de las BPG, estas de igual forma deben tener el registro ICA. Además, los medicamentos veterinarios deben ir organizados y direccionados de acuerdo con su principio y acción terapéutica, separados de otros insumos como fertilizantes, plaguicidas o alimentos.

          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema1/img11.png', alt='')

        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            h3 Manejo integrado de residuos y plagas
            p Para esto se debe realizar un protocolo de recolección, clasificación, disposición, almacenamiento y rutas de residuos en la unidad productiva, asignando responsables y demás. En cuanto al manejo de plagas se debe elaborar un programa escrito de control de plagas y roedores, que sirve como guía procedimental para los operarios de la unidad productiva, este debe incluir los registros de la aplicación de los productos y las herramientas utilizadas en esta labor.

          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema1/img12.png', alt='')

        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            h3 Suministro y calidad del agua
            p Una vez al año, como mínimo, se debe efectuar un análisis químico, físico y microbiológico del agua del predio, en especial de la que es destinada para el consumo animal; además, se debe tener en cuenta los materiales, calidad, capacidad, limpieza y desinfección de los tanques de almacenamiento de agua. En cada etapa los animales requieren de agua limpia y fresca, sobre todo en las fases productivas.

          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema1/img13.png', alt='')

          
        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            h3 Bienestar animal
            p Existen tópicos de gran importancia en la producción animal como el maltrato, estrés, manejo, instalaciones, embarque, transporte y sacrificio que deben considerarse en los sistemas de producción ganadera (Uribe, et al., 2011). Los principios básicos del tema de bienestar en las producciones pecuarias se basan en las cinco libertades propuestas para el mismo de las cuales se han derivado las diferentes prácticas que buscan que los animales se encuentren en las mejores condiciones productivas.

          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema1/img14.png', alt='')

        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            h3 Personal
            p El componente humano forma parte fundamental en la producción animal y, por tanto, debe asegurarse de que este no sea susceptible a adquirir o transmitir enfermedades que puedan poner en riesgo el producto, por lo cual se debe garantizar que los trabajadores estén afiliados a EPS y ARL, y que se realicen una evaluación médica por lo menos una vez por año. En las instalaciones debe adecuarse un lugar para el botiquín de primeros auxilios y existir un grupo capacitado de personas que pueda responder a cualquier tipo de eventualidad.

          .col-md-6.p-3
            figure
              img(src='@/assets/curso/temas/tema1/img15.png', alt='')

    separador
    #t_1_2.titulo-segundo.color-acento-contenido
      h2 1.2 Certificación     

    .row.justify-content-center 
      .col-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-left")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img16.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Certificarse en BPG en la unidad productiva es de gran importancia, pues los productores tienen una mayor posibilidad de que sus productos cumplan con los estándares de alta calidad, reciban un mejor precio y tengan acceso a los mercados nacionales e internacionales, disfrutando de los beneficios de los acuerdos comerciales establecidos con diferentes países. 

    p(data-aos="zoom-in").mt-5 La autoridad competente en certificar la unidad productiva es el Instituto Colombiano Agropecuario ICA, el cual evalúa y emite concepto de acuerdo a la aplicación de los criterios establecidos por la Resolución 76509 y la forma 3-519 contabilizando los aspectos fundamentales (F), los mayores (My) y los menores (Mn) para determinar los porcentajes de incumplimiento y fijar un plan de trabajo que permita sobre todo, llevar los criterios fundamentales al 100 %, los criterios mayores por encima de 80 % y los criterios menores a un rango mejor que 60 % para garantizar efectivas buenas prácticas ganaderas en la producción de porcícola, lo que será suficiente para la expedición del certificado de Buenas Prácticas Ganaderas BPG en la producción de porcinos por parte del ICA y permitirá obtener beneficios en la empresa tanto en el plano interno como en el externo, lo que le permitirá obtener una ventaja competitiva en temas de producto, mercado, medio ambiente, bienestar animal, disminución de riesgos laborales, entre otros.
    p(data-aos="zoom-in") A continuación, se describen los diferentes porcentajes y los conceptos emitidos para certificación de acuerdo a la evaluación realizada en las unidades productivas.

    .col-12.titulo-sexto.color-acento-contenido.mt-5(data-aos="fade-right")
      p.titulo.pb-0.mb-0 <b>Tabla 1.</b> <i>Totalización de criterios para certificación de BPG </i>

    .tabla-a.color-acento-contenido.mt-5(data-aos="fade-left")
      table
        caption Nota. Tomada de lista de chequeo para predios productores de porcinos con destino al sacrificio.
        thead
          tr
            th 
            th Total criterios
            th N.° criterios 
            th N.° criterios a cumplir
            th % de criterios a cumplir
            th Criterios cumplidos
            th % de criterios cumplidos
        tbody
          tr
            td Fundamentales (F)
            td.text-center 23
            td 
            td 
            td.text-center 100 %
            td
            td
          tr
            td Mayores (My)
            td.text-center 34
            td 
            td 
            td.text-center 80 %
            td
            td
          tr
            td Menores (Mn)
            td.text-center 5
            td 
            td 
            td.text-center 60 %
            td
            td

    .row.justify-content-center.mt-5
      .col
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-left")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img17.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Después de haber realizado el diagnóstico, aplicando la lista de chequeo y posteriormente realizando las acciones correctivas, el productor deberá solicitar la visita de auditoría ante el ICA para que en un tiempo no mayor a 15 días posteriores a la solicitud se le realice la visita donde, a través de un informe y una lista de chequeo, se verificará el cumplimiento de lo establecido en la Resolución 76509 del 25 de septiembre del 2020.

    p(data-aos="zoom-in").mt-5 El resultado de esta visita dará el concepto de certificable o aplazado de acuerdo con lo siguiente:

    .row.justify-content-center.mt-5
      .col-10
        TabsA.color-acento-contenido.mb-5
          .tarjeta.color-acento-contenido--borde.p-4(titulo="Certificable")
            .row.justify-content-center
              .col-auto
                p El concepto técnico será certificable cuando el predio cumpla con el 100 % de los criterios fundamentales, mínimo el 80 % de los criterios mayores y mínimo 60 % de los criterios menores, ante lo cual se expedirá el certificado de Buenas Prácticas Ganaderas BPG en la producción de porcina (Resolución 76509 de 2020 del ICA, por medio de la cual se establecen los requisitos para obtener la certificación en Buenas Prácticas Ganaderas BPG en la producción porcina).
          .tarjeta.color-acento-contenido--borde.p-4(titulo="Aplazado")
            .row.justify-content-center
              .col-auto
                p El concepto técnico  será aplazado, cuando el predio cumpla con menos del 100 % de los criterios fundamentales, y/o menos del 80 % de los criterios mayores, y/o menos del 60 % de los criterios menores; las no conformidades encontradas se pueden corregir en un plazo máximo de tres (3) meses, contados a partir de la fecha de la visita. Se considerará abandonada la solicitud, sin perjuicio de que pueda realizar una nueva solicitud con el cumplimiento de todos los requisitos exigidos (Resolución 76509 de 2020 del ICA).
                
    separador
    #t_1_3.titulo-segundo.color-acento-contenido
      h2 1.3 Recursos 

    .row.justify-content-center
      .col
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-left")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img18.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Los recursos comprenden todo, desde los equipos, elementos y fondos económicos hasta el volumen de empleados, es decir, todo lo que sea necesario para la operatividad y funcionamiento de una unidad productiva, plan de implementación o proyecto.
            br
            br
            p Para adquirir recursos se debe realizar la gestión del proceso de planificación y programación de los recursos y actividades para implementar un plan o proyecto, luego se formula un plan que, para ser eficaz, debe establecer recursos específicos, incluidos los recursos humanos, financieros, técnicos y físicos, además de todas las actividades necesarias durante la ejecución de un proyecto, plan o iniciativa de manera efectiva.

    p(data-aos="zoom-in").mt-5 Así, se puede dar un cuadro completo del sistema, teniendo en consideración los recursos que pueden clasificarse en cinco tipos distintos: 

    .tarjeta.tarjeta--azul.p-4.mt-5
      SlyderA(tipo="b")
        .row
          .col
            figure
              img(src='@/assets/curso/temas/tema1/img19.png', alt='')
              figcaption Recursos físicos

        .row
          .col
            figure
              img(src='@/assets/curso/temas/tema1/img20.png', alt='')
              figcaption Recurso humano

        .row
          .col
            figure
              img(src='@/assets/curso/temas/tema1/img21.png', alt='')
              figcaption Propiedad intelectual

        .row
          .col
            figure
              img(src='@/assets/curso/temas/tema1/img22.png', alt='')
              figcaption Software y métodos

        .row
          .col
            figure
              img(src='@/assets/curso/temas/tema1/img23.png', alt='')
              figcaption Recursos financieros

    separador
    #t_1_4.titulo-segundo.color-acento-contenido
      h2 1.4. Cronograma de actividades 

    .row.justify-content-center
      .col
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-left")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img24.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Un cronograma es la planeación de las actividades para ejecución en una línea de tiempo, por ende, esta herramienta permite visualizar el plan de implementación en todas sus dimensiones y el tiempo que este requiere para llevarse a cabo, siendo más claros un cronograma permite hacerse un mejor panorama de cómo encajan todos los puntos del plan, cómo interactúan las fases y cuál es el proceso para lograrlo en un determinado tiempo, muchas veces vinculando también el equipo de personas que participan en los mismos.

    p(data-aos="zoom-in").mt-5 Para crear un cronograma se debe tener en cuenta el tiempo total definido para la implementación, los objetivos o metas, las actividades que se incluyen por más sencillas que parezcan, como documentación, recopilación de información, inspección de la unidad productiva, diagnóstico de la unidad productiva, elaboración del plan, reuniones, divulgación, entre otras. Cuanto más específico mejor quedará el cronograma y, por tanto, las actividades serán mejor planeadas y ejecutadas en los tiempos requeridos.
</template>
<script>
export default {
  name: 'Tema1',
  components: {},
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
