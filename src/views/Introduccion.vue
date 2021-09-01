<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal(data-aos="flip-down")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    p.mb-5 Apreciado aprendiz, bienvenido a este momento de aprendizaje enfocado en diferentes temáticas que giran alrededor del traslado inicial, intermedio y final de restos mortales. Antes de entrar a comprender el contenido necesario para el desarrollo de su aprendizaje, explore el siguiente recurso de aprendizaje:
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row(titulo="¿Cómo surge este componente de formación?").align-items-center
        .col-4
          figure
            img(src='@/assets/curso/img1.svg', style="width: auto" ,alt='Texto que describa la imagen').m-auto
        .col-8
          p.mb-0 Este momento surge desde la necesidad de identificar el proceso de traslado de unos restos mortales a partir de unos protocolos de servicio y una normativa.
      div(titulo="¿Qué se ha diseñado para aprender?")
        .row.align-items-center
          .col-4
            figure
              img(src='@/assets/curso/img2.svg', style="width: auto" ,alt='Texto que describa la imagen').m-auto
          .col-8
            p Ante esta necesidad, se ha seleccionado y organizado un contenido temático pensado para usted. 
            p.mb-0 Su lectura y comprensión generará capacidades en usted para conocer, pensar, actuar ante el evento del traslado de unos restos mortales. Una experiencia que debe ser atendida con respeto por las creencias de quienes están involucrados.
      div(titulo="¿Cómo puedo aprender?")
        .row
          .col-12
            p.mb-5 Su aprendizaje está determinado por:
            figure
              img(src='@/assets/curso/img3.svg', style="width: auto" ,alt='Texto que describa la imagen').m-auto
      div(titulo="¿Qué se espera de usted?")
        .row.align-items-center
          .col-4
            figure
              img(src='@/assets/curso/img4.svg', style="width: auto" ,alt='Texto que describa la imagen').m-auto
          .col-8
            p Se espera que la apropiación del contenido tenga sentido cuando usted lo integre con sus actividades de aprendizaje y su contexto laboral. Recuerde que acá apenas inicia su aprendizaje, porque este continúa a lo largo de su vida. 
            .h4 ¡Bienvenido!
    p.mb-0 Para la elaboración de este componente, se abordaron varios autores conocidos en traslado de restos mortales, de quienes se han citado y referenciado conceptos y ejemplos para los fines educativos de esta materia, en el entendido de que el conocimiento es social y, por lo tanto, es para ser usado por quienes necesitan adquirirlo. Se espera que este documento sea útil para todos, aprendices y lectores en general, que estén interesados en acercarse a asuntos básicos de tanatopraxia.

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
