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
      h2#t_1_1 2.1 Protocolos de manejo ambiental

    p.mb-5 Como parte del sistema de gestión de calidad a nivel ambiental se hace necesario definir protocolos que den pautas respecto a los procesos productivos, ya que la mejora de estos permite un control de la contaminación ambiental en las empresas del sector avícola y su impacto en la comunidad las cuales podrá profundizar a continuación dando clic sobre cada huevo. 

    TabsB.color-primario.mb-5
      .py-4.py-md-5.px-5(titulo="Protocolos de manejo ambiental")
        .row
          .col-md-12.mb-4.mb-md-0
            p Son acciones encaminadas a evitar los impactos, efectos y riesgos ambientales, que pueden causar impactos negativos o daño a las personas, al medio ambiente y/o a la propiedad privada durante la ejecución de una actividad o proyecto.
      
      .py-4.py-md-5.px-5(titulo="Medidas de Prevención")
        .row
          .col-md-12.mb-4.mb-md-0
            p Las medidas de prevención tienen por finalidad disminuir o evitar que aparezcan efectos desfavorables o indeseables a consecuencia de los riesgos ambientales, a la salud humana o en el medio ambiente, y que pudieran provocar una pérdida, disminución, detrimento o menoscabo significativo a uno o más elementos del mismo, a consecuencia de la ejecución de una actividad o proyecto. 

      .py-4.py-md-5.px-5(titulo="Medidas de control")
        .row
          .col-md-12.mb-4.mb-md-0
            p Estas se consideran una serie de medidas destinadas a enfrentar con éxito los riesgos identificados en cada una de las etapas de una actividad o proyecto toda vez que ocurra un riesgo específico, minimizando los daños a los trabajadores, a comunidades vecinas, al medio ambiente circundante y a las instalaciones.

      .py-4.py-md-5.px-5(titulo="Medidas de mitigación")
        .row
          .col-md-12.mb-4.mb-md-0
            p Estas se entienden como la implementación o aplicación de cualquier política, estrategia, obra y/o acción tendiente a minimizar los impactos adversos que puedan presentarse en cierta actividad productiva o durante las etapas de ejecución de un proyecto y mejorar la calidad ambiental aprovechando las oportunidades existentes.
      
      .py-4.py-md-5.px-5(titulo="Medidas de compensación")
        .row
          .col-md-12.mb-4.mb-md-0
            p Son las actividades dirigidas a retribuir a las comunidades, las regiones, localidades y entorno natural, por los impactos o efectos negativos generados por un proyecto, que no puedan ser evitados, corregidos, mitigados o sustituidos.

    Separador 

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_1_1 2.2 Normativa sobre el manejo ambiental 

    p.mb-5 La normatividad planteada para el manejo ambiental se ciñe particularmente en el plan de manejo ambiental, el cual debe ser diseñado para cada proyecto o actividad en específico; en el caso de la industria avícola hay una gran ventaja del modelo a seguir el cual está contenido en “La Guía Ambiental Para El Subsector Avícola”, la que ilustra a los productores del sector en el diseño y los puntos a seguir esta guía se tratará más adelante. 

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
