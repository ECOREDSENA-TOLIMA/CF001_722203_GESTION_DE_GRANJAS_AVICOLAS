<template lang="pug">
.curso-main-container.pb-3.tema5
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Huella de carbono

    .d-flex.flex-wrap.mb-5
      .col-xl-7.pe-xl-5.d-flex.flex-wrap.align-items-center.order-2.order-xl-1
        .cajon.color-acento-contenido.p-4.d-flex.flex-wrap(data-aos="fade-right")
          .col-md-11.ps-lg-4
            p Es uno de estos nuevos términos que cada vez están más presentes en nuestra actividad. Se trata de un indicador ambiental clave, que refleja los gases emitidos por un individuo o empresa.
              br
              br
              | Estos gases que se acumulan en la atmósfera son lo que producen el efecto invernadero. En resumidas cuentas, se puede definir la huella de carbono como el impacto que deja la actividad humana sobre el medio ambiente. Es decir, la marca ambiental que genera una persona, producto u organización sobre el planeta debido a sus acciones diarias, totalizadas según parámetros de emisiones de dióxido de carbono (CO₂) y otros gases de efecto invernadero (GEI) liberadas a la atmósfera.  
      img.mb-4.mb-xl-0.col-xl-5.mx-auto.order-1.order-xl-2(src="@/assets/curso/temas/tema6/img-1.png" style="max-width: 500px")

    p A continuación, se revisarán otros temas que son vitales para entender cómo cada ser humano es responsable del cuidado del medio ambiente en el planeta y cómo impacta la sociedad en general. 

    Separador 
    #t_6_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 6.1 Importancia ambiental y económica 

    .col-12.d-flex.flex-wrap.align-items-center.p-2.mb-5
      .col-12.col-md-3.col-lg-1
        img.mb-4.mb-md-0.mx-auto(src="@/assets/curso/temas/tema6/decorador-1.svg" data-aos="fade-right" style="max-width: 100px")
      p.col.mb-0.col-md-9.col-lg-11.ps-lg-4(data-aos="fade-left") La Huella de Carbono (HC) tiene una gran importancia en el medio ambiente como indicador de sostenibilidad y de impacto hacia el cambio climático, ya que aporta información sobre la cantidad de Gases de Efecto Invernadero (GEI) que se emite a la atmósfera en el desarrollo de una actividad humana, ya sea esta individual o colectiva.
        br
        br
        | En el ámbito productivo esto significa que, se deben controlar las emisiones de gases, las cuales se pueden identificar y reducir, lo cual afectaría positivamente los costos de producción, aumentando la eficiencia y competitividad de la empresa y cumpliendo así con las pautas de entidades internacionales en el tema. 

    .d-flex.flex-wrap.mb-5
      .col-xl-12.pe-xl-1.d-flex.flex-wrap.align-items-center.order-2.order-xl-1
        .color-primario.p-4.d-flex.flex-wrap(data-aos="fade-right" style="background-color:#FFDBDB")
          .col-md-12.ps-lg-1
            p.mb-0 Como consecuencia del cambio climático, se han desarrollado iniciativas internacionales que promueven el cuidado del medio ambiente, con el fin de reducir las emisiones que se lanzan a la atmósfera, esto necesariamente ha llevado a la creación de entidades certificadoras que determinan si una empresa (para este caso: sector avícola), país o población está cumpliendo con lo pactado a nivel mundial, a continuación, se tocarán esos temas.  

    Separador 
    #t_6_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 6.2 Regulaciones, entidades certificadoras y requerimientos para ingresar a los mercados internacionales

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema6/img-2.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El impacto ambiental de la Huella de Carbono, se controla a través de unas mediciones en las emisiones de gases que son lanzados a la atmósfera durante todo el ciclo de vida. Hay normativas internacionales como ISO 14064, ISO 14069, ISO 14067, PAS 2050 o GHG Protocolo, entre otras, que recogen este tipo de propuestas.
          br
          br
          | La huella de carbono se mide en masa de CO2 equivalente. Según el tamaño de la huella, es posible implementar una estrategia de gestión de emisiones, a través de diferentes programas. 

    p.mb-5 En Colombia está regulada la huella de carbono principalmente a través de la siguiente reglamentación, para conocerla revise el objeto digital de aprendizaje que a continuación se muestra. 

    ImagenInfografica.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/temas/tema6/img-3.svg', alt='Texto que describa la imagen')

      .tarjeta.color-primario.p-3(x="32.7%" y="20.5%" numero="")
        p Por medio de la cual se establece el control, prevención y mitigación de la emisión de gases de invernadero.

      .tarjeta.color-primario.p-3(x="37.9%" y="49.3%" numero="")
        p Por el cual se establecen medidas para tratar con el cambio climático desde diferentes sectores.

      .tarjeta.color-primario.p-3(x="32.6%" y="76%" numero="")
        p Por la cual se establece la creación del registro de emisión de gases efecto invernadero.

    p.mb-5 A continuación, se va a tratar un tema clave para el sector avícola colombiano, ya que muestra el avance del mismo en términos de reglamentaciones o pautas que se han desarrollado para esto le invito a revisar el tema ¨Guía ambiental para el subsector avícola¨ de FENAVI por su cuenta con el fin de reforzar su aprendizaje. 

    .row.justify-content-center.align-items-center
      .col-md-10.col-lg-9.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/tema1/decorador-2.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4 Guía ambiental para el subsector avícola   
                  p.text-small Para profundizar en el aprendizaje puede revisar el siguiente documento: Guía ambiental para el subsector avícola.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://fenavi.org/wp-content/uploads/2018/05/GUIA_AMBIENTAL_SUBSECTOR_AVICOLA.pdf" target="_blank")
                    span Descargar
                    i.fas.fa-file-download


</template>

<script>
export default {
  name: 'Tema6',
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
