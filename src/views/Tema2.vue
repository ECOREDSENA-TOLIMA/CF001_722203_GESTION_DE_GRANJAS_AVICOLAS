<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Manejo ambiental 

    .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down-left")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img-12.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Son todas las acciones encaminadas a mejorar los procesos productivos con el fin de reducir los niveles de contaminación ambiental a través de evaluaciones del impacto ambiental, la estructuración del sistema de manejo y el control de los procesos de acuerdo con la política existente.

    Separador

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_2_1 2.1 Protocolos de manejo ambiental

    p.mb-5 Como parte del sistema de gestión de calidad a nivel ambiental se hace necesario definir protocolos que den pautas respecto a los procesos productivos, ya que la mejora de estos permite un control de la contaminación ambiental en las empresas del sector avícola y su impacto en la comunidad las cuales podrá profundizar a continuación dando clic sobre cada huevo. 

    TabsB.color-primario.mb-5
      .py-4.py-md-5.px-5(titulo="Protocolos de manejo ambiental")
        .row
          .col-md-12.mb-4.mb-md-0
            p Son acciones encaminadas a evitar los impactos, efectos y riesgos ambientales, que pueden causar impactos negativos o daño a las personas, al medio ambiente y/o a la propiedad privada durante la ejecución de una actividad o proyecto.
      
      .py-4.py-md-5.px-5(titulo="Medidas de prevención")
        .row
          .col-md-12.mb-4.mb-md-0
            p Las medidas de prevención tienen por finalidad disminuir o evitar que aparezcan efectos desfavorables o indeseables a consecuencia de los riesgos ambientales, a la salud humana o en el medio ambiente, y que pudieran provocar una pérdida, disminución, detrimento o menoscabo significativo a uno o más elementos del mismo, a consecuencia de la ejecución de una actividad o proyecto. 

      .py-4.py-md-5.px-5(titulo="Medidas de control")
        .row
          .col-md-12.mb-4.mb-md-0
            p Estas medidas se consideran una serie de acciones diseñadas para abordar eficazmente los riesgos identificados en cada etapa de una actividad o proyecto. Su objetivo es reducir al mínimo los posibles daños a los trabajadores, comunidades vecinas, entorno ambiental y las instalaciones en caso de que se produzca un riesgo específico.

      .py-4.py-md-5.px-5(titulo="Medidas de mitigación")
        .row
          .col-md-12.mb-4.mb-md-0
            p Estas se entienden como la implementación o aplicación de cualquier política, estrategia, obra y/o acción tendiente a minimizar los impactos adversos que puedan presentarse en cierta actividad productiva o durante las etapas de ejecución de un proyecto y buscan mejorar la calidad ambiental aprovechando las oportunidades existentes.
      
      .py-4.py-md-5.px-5(titulo="Medidas de compensación")
        .row
          .col-md-12.mb-4.mb-md-0
            p Estas actividades se orientan hacia la compensación de comunidades, regiones, localidades y el entorno natural, como respuesta a los impactos o efectos adversos causados por un proyecto. Estos impactos, cuando no pueden ser evitados, corregidos, mitigados o reemplazados, se buscan equilibrar mediante acciones que contribuyan a restaurar o mejorar la calidad de vida y el bienestar de las áreas afectadas.

    Separador 

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_2_2 2.2 Normativa sobre el manejo ambiental 

    p.mb-5 La normativa establecida para el manejo ambiental se enfoca especialmente en el desarrollo de un plan de manejo ambiental, el cual debe ser adaptado a cada proyecto o actividad en particular. En el ámbito de la industria avícola, existe una ventaja significativa en la forma de un modelo preestablecido que se encuentra en "La guía ambiental para el subsector avícola". Esta guía ofrece orientación a los productores del sector sobre cómo diseñar y seguir el plan adecuado.

    .row.justify-content-center.align-items-center.mb-4
      .col-md-10.col-lg-9.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/tema1/decorador-2.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4 Guía ambiental para el subsector avícola  
                  p.text-small Para profundizar en el tema sobre el manejo ambiental puede revisar el siguiente documento.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://fenavi.org/publicaciones-programa-ambiental/guia-ambiental-para-el-subsector-avicola/" target="_blank")
                    span Descargar
                    i.fas.fa-file-download





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
