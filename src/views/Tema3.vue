<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal(data-aos="flip-down")
      .titulo-principal__numero
        span 3
      h1 Creencias y servicio en un traslado
    .row.align-items-center
      .col-lg-6.mb-4.mb-lg-0
        p.mb-4 Se tiene evidencia de que desde hace miles de años el hombre ha tenido rituales funerarios específicos para tramitar las emociones y los sentimientos tras la muerte de una persona que pertenece a su comunidad o grupo familiar. El ritual funerario permite que los duelos de las personas se realicen con mayor facilidad, pues se usan elementos que ayudan a despedir y a significar esos momentos finales, a través del uso de flores, música, fotos, videos o elementos varios que hayan sido importantes para el fallecido. Todos estos elementos permiten la expresión de las emociones hacia los restos mortales. Estas acciones desarrolladas durante el ritual hacen de esa experiencia un momento único.
        .cajon.color-secundario.p-4
          p.mb-0 En los rituales funerarios se tiene en cuenta la última voluntad de la persona, en caso tal de haberla expresado. En este sentido, las funerarias, en su cadena de servicios, tratan de cumplir estas peticiones porque finalmente el servicio funerario está diseñado para las despedidas significativas, dignas y honrosas del fallecido.
      .col-lg-6
        figure(data-aos="fade-left")
          img(src='@/assets/curso/img14.png', style="width: auto " ,alt='Texto que describa la imagen').m-auto
    .row.justify-content-center.my-5
      .col-lg-10
        p Los rituales han evolucionado hasta la actualidad y tienen formas y manifestaciones diferentes en todo el mundo. Todos los rituales funerarios se basan en las creencias y son acompañados por símbolos que refuerzan dichas creencias. En el contexto colombiano, se deben respetar las creencias en las cuales está inmerso un ritual funerario, ya que la Constitución (1991) colombiana determina, en su artículo 19, la libertad de cultos, el derecho de toda persona a profesar libremente su religión y difundirla en forma individual o colectiva, y la igualdad ante la ley de todas las confesiones religiosas e iglesias. Este artículo está vigente en el momento de un deceso. Como consecuencia, en las entidades funerarias se respetan completamente las decisiones que tome cada familia con respecto al desarrollo del servicio funerario; la familia es libre de decidir si se realizan ceremonias religiosas o velaciones, según sus credos.
    .bloque-texto-a.color-primario.p-4.p-md-3.mb-5(data-aos="fade-right")
      .row.m-0.align-items-center.justify-content-between
        .col-lg-8.mb-4.mb-lg-0
          .bloque-texto-a__texto.p-4
            p En todas las empresas funerarias, deben estar en capacidad de ofrecer opciones para cada uno de los requerimientos sociales y culturales de las comunidades que constituyen los territorios donde hacen presencia. Las empresas, como prestadoras del servicio funerario, deben tener la consigna de ser siempre respetuosos con las otras formas o manifestaciones de los rituales y creencias. Durante el inicio del traslado de los restos mortales, la empresa funeraria, y especialmente los funcionarios encomendados para dicha función, debe atender las solicitudes de las personas para el desarrollo del ritual y convertirse en aquellas personas que custodian la dignidad del cuerpo fallecido.
        .col-lg-4
          figure
            img(src='@/assets/curso/img28.svg', style="width: auto " ,alt='Texto que describa la imagen').m-auto
    .row.justify-content-center
      .col-lg-10
        p.mb-0 Para finalizar este momento de aprendizaje, se debe recordar que, cuando un funcionario es designado como un custodio de un cuerpo o restos mortales, no se le está permitido tomar fotografías de las condiciones de la muerte y mucho menos compartirlas. Las causas de la muerte y la manera de la muerte deben ser tratadas con la mayor confidencialidad y respeto posible, no está permitido dar información a terceros o personas ajenas al servicio sin la autorización expresa del familiar o del responsable del servicio.

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

<style lang="sass" scoped></style>
