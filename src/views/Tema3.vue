<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Normatividad ambiental  

    .d-flex.flex-wrap.mb-5
      .col-xl-7.pe-xl-5.d-flex.flex-wrap.align-items-center.order-2.order-xl-1
        .cajon.color-acento-contenido.p-4.d-flex.flex-wrap
          .col-md-11.ps-lg-4
            p En consonancia con los requisitos tanto nacionales como internacionales en el sector avícola, la normativa ambiental ha sido objeto de regulación constante. Esta adaptación continua se ajusta a las demandas de producción, al crecimiento de la industria y a sus implicaciones medioambientales. Es por esta razón que la normativa se convierte en una herramienta valiosa para los avicultores, permitiéndoles mejorar sus procesos productivos considerando prácticas de producción limpias y sostenibles y ateniéndose a la legislación en vigor.
              br
              br
              | Según FENAVI (2018), el objetivo de la gestión ambiental en la producción avícola radica en prevenir, minimizar y controlar los efectos derivados de sus operaciones. Estos efectos abarcan diversas áreas, como la regulación del uso del agua, el control de la contaminación del suelo y del aire. Además, es esencial considerar la clasificación y correcto tratamiento de los residuos, así como la gestión adecuada de las mortalidades, entre otros aspectos relevantes.
      img.mb-4.mb-xl-0.col-xl-5.mx-auto.order-1.order-xl-2(src="@/assets/curso/temas/tema3/img-1.png" style="max-width: 500px")

    p Es importante resaltar que la implementación del programa de gestión ambiental debe ir de la mano con otras acciones, como el desarrollo de habilidades para cumplir con las regulaciones actuales y la formación constante de todo el personal en cuestiones ambientales. Además, es fundamental llevar a cabo un seguimiento exhaustivo del progreso y la ejecución del componente ambiental, asegurándose de que se logren cumplir las metas y objetivos establecidos.
    p.mb-5 A continuación, encontrará una tabla donde se sintetiza la información sobre normatividad relacionada con el sector avícola en Colombia.

    Separador

    .row.justify-content-center.align-items-center.mb-5.mt-4
      .col-12.col-md-10.px-0(data-aos="fade-down")
        .titulo-sexto.color-primario(data-aos="fade-right")
          h5 Tabla 1.
          span <em>Reglamentación del sector avícola en Colombia</em>
        .tabla-a.color-acento-contenido 
          table
            thead
              tr
                th NOMBRE 
                th TEMA 
                th DESCARGAR 
            tbody
              tr
                td.text-center Política Nacional de Producción y Consumo Sostenible, 2010.
                td Este documento combina y actualiza la Política Nacional de Producción más Limpia y el Plan Nacional de Mercados Verdes como estrategias gubernamentales en Colombia. Estas estrategias fomentan la conexión entre la mejora ambiental y la transformación productiva en aras de mejorar la competitividad empresarial.
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://www.minambiente.gov.co/wp-content/uploads/2021/06/polit_nal_produccion_consumo_sostenible.pdf" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download

              tr
                td.text-center Política Nacional para la Gestión Integral Ambiental del Suelo (GIAS), 2013. 
                td Se presenta la Política Nacional para la Gestión Integral Ambiental del Suelo (GIAS) con el fin de aportar a la conservación y uso sostenible de este componente determinante de los ciclos del agua, del aire y de los nutrientes e indispensable para la preservación de la biodiversidad y sus servicios ecosistémicos.
                td.text-center
                  a.boton.color-primario.texto-blanco(:href="obtenerLink('/downloads/DI_CF1_Anexo1_Politica-de-gestion-integral-del-suelo minam.pdf')" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download
              tr
                td.text-center Política Nacional para la Gestión Integral del Recurso Hídrico, 2010.
                td El presente documento contiene la Política Nacional para la Gestión Integral del Recurso Hídrico (PNGIRH), que establece los objetivos, estrategias, metas, indicadores y líneas de acción estratégica para el manejo del recurso hídrico en el país en un horizonte de 12 años.
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://www.minambiente.gov.co/wp-content/uploads/2021/10/Politica-nacional-Gestion-integral-de-recurso-Hidrico-web.pdf" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download
              tr
                td.text-center Política Ambiental para la Gestión Integral de Residuos o Desechos Peligrosos, 2005. 
                td Esta política tiene como objetivo principal promover el uso y manejo responsable de los residuos peligrosos. Estos residuos son reconocidos como fuentes potenciales de riesgo tanto para el medio ambiente como para la salud humana.
                td.text-center
                  a.boton.color-primario.texto-blanco(href="http://www.ideam.gov.co/documents/51310/526371/POLITICA+AMBIENTAL+PARA+LA+GESTION+INTEGRAL+DE+RESPEL.pdf/fb42059d-77ec-423b-8306-960dee6bb9c6" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download
              tr
                td.text-center Resolución 668 de 2016. 
                td Por la cual se reglamenta el uso racional de bolsas plásticas y se adoptan otras disposiciones.
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://www.minambiente.gov.co/documento-normativa/resolucion-668-de-2016/" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download
              tr
                td.text-center Ley 1333 de 2009. 
                td Por la cual se establece el procedimiento sancionatorio ambiental y se dictan otras disposiciones.
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=36879" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download
              
              tr
                td.text-center Resolución 2087 de 2014. 
                td Por la cual se adopta el Protocolo para el monitoreo, control y vigilancia de olores ofensivos.
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://fenavi.org/wp-content/uploads/2018/05/Resoluci%C3%B3n-2087-de-2014-Protocolo-Monitoreo-control-y-Vigilancia-de-Olores-Ofensivos-1.pdf" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download

              tr
                td.text-center Resolución 1207 de 2014. 
                td Por la cual se adoptan disposiciones relacionadas con el uso de aguas residuales tratadas. 
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://fenavi.org/wp-content/uploads/2018/05/Resoluci%C3%B3n_1207_2014-Reuso-aguas-tratadas-1.pdf" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download

              tr
                td.text-center Ley 1672 de 2013. 
                td Por la cual se establecen los lineamientos para la adopción de una política pública de gestión integral de residuos de aparatos eléctricos y electrónicos (RAEE), y se dictan otras disposiciones.
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://fenavi.org/wp-content/uploads/2018/05/ley_1672_2013-1.pdf" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download

              tr
                td.text-center Resolución ICA 3650 de 2014. 
                td Por medio de la cual se establecen los requisitos para el registro como productor de material genético aviar y expedición de licencias de venta de material genético aviar.
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://www.ica.gov.co/getattachment/3c2f3642-85a5-4622-91b5-5a31597c2cb4/2014R3-(1).aspx" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download

              tr
                td.text-center Resolución ICA 3652 de 2014.  
                td Por medio de la cual se establecen los requisitos para la certificación de granjas avícolas bioseguras de engorde y se dictan otras disposiciones.
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://www.ica.gov.co/getattachment/124802ad-c49c-470d-809e-a9ce5ad3db76/2014R3652.aspx" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download

              tr
                td.text-center Resolución ICA 3651 de 2014.   
                td Por medio de la cual se establecen los requisitos para la certificación de granjas avícolas bioseguras de postura y/o levante y se dictan otras disposiciones. 
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://www.ica.gov.co/getattachment/b8cb4efd-a1b4-409e-a11d-c81b91f59025/2014R3651.aspx#:~:text=Que%20el%20Instituto%20Colombiano%20Agropecuario,importancia%20econ%C3%B3mica%20a%20nivel%20nacional." target="_blank")
                    span Descargar PDF
                    i.fas.fa-download





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
