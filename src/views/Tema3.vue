<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Normatividad ambiental  

    .d-flex.flex-wrap.mb-5
      .col-xl-8.pe-xl-4.d-flex.flex-wrap.align-items-center.order-2.order-xl-1
        .cajon.color-acento-contenido.p-4.d-flex.flex-wrap(data-aos="fade-right")
          .col-md-11.ps-lg-4
            p De acuerdo a los requerimientos presentados en el sector avícola a nivel internacional y nacional, se ha venido reglamentando la normatividad ambiental, la cual se adapta continuamente a las necesidades de la producción, el crecimiento de la industria y los impactos ambientales de la misma; por eso es que esta es una herramienta que le permite a los avicultores mejorar sus procesos productivos teniendo en cuenta las producciones limpias y sostenibles, al tener que usar la legislación vigente. 
              br
              br
              | De acuerdo a FENAVI (2018), La gestión ambiental dentro la producción avícola tiene como objeto: prevenir, minimizar y controlar los impactos derivados de sus actividades, tales como: hacer un uso adecuado y control en la contaminación del agua, el suelo y el aire, además se debe tener en cuenta la clasificación y el manejo adecuado de residuos y las mortalidades, entre otros.
      img.mb-4.mb-xl-0.col-xl-4.mx-auto.order-1.order-xl-2(src="@/assets/curso/temas/tema3/img-1.png" data-aos="fade-left" style="max-width: 400px")


    p Es relevante recalcar que, la ejecución del programa de gestión ambiental se debe acompañar de otras actividades como la generación de competencias para el cumplimiento de la normatividad vigente y la capacitación continua de todo el personal en el área ambiental. Además, se debe hacer seguimiento al desarrollo y ejecución del componente ambiental, cuidando de que se cumplan sus metas y objetivos. 
    p.mb-5 A continuación, encontrará una tabla donde se sintetiza la información sobre normatividad relacionada con el sector avícola en Colombia.

    Separador

    .row.justify-content-center.align-items-center.mb-5.mt-4
      .col-12.col-md-10.px-0(data-aos="fade-down")
        .tabla-a.color-primario 
          table
            thead
              tr
                th NOMBRE 
                th TEMA 
                th DESCARGAR 
            tbody
              tr
                td Política Nacional de Producción y Consumo Sostenible, 2010.
                td En este documento se actualizan e integran la Política Nacional de Producción más Limpia y el Plan Nacional de Mercados Verdes como estrategias del Estado Colombiano que promueven y enlazan el mejoramiento ambiental y la transformación productiva a la competitividad empresarial. 
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://www.minambiente.gov.co/wp-content/uploads/2021/06/polit_nal_produccion_consumo_sostenible.pdf" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download

              tr
                td Política Nacional para la Gestión Integral Ambiental del Suelo (GIAS), 2013. 
                td Se presenta la Política Nacional para la Gestión Integral Ambiental del Suelo (GIAS) con el fin de aportar a la conservación y uso sostenible de este componente determinante de los ciclos del agua, del aire y de los nutrientes e indispensable para la preservación de la biodiversidad y sus servicios ecosistémicos.
                td.text-center
                  a.boton.color-primario.texto-blanco(:href="obtenerLink('/downloads/DI_CF1_Anexo1_Politica-de-gestion-integral-del-suelo minam.pdf')" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download
              tr
                td Política Nacional para la Gestión Integral del Recurso Hídrico, 2010.
                td El presente documento contiene la Política Nacional para la Gestión Integral del Recurso Hídrico (PNGIRH) que establece los objetivos, estrategias, metas, indicadores y líneas de acción estratégica para el manejo del recurso hídrico en el país en un horizonte de 12 años. 
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://www.minambiente.gov.co/wp-content/uploads/2021/10/Politica-nacional-Gestion-integral-de-recurso-Hidrico-web.pdf" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download
              tr
                td Política Ambiental para la Gestión Integral de Residuos o Desechos Peligrosos, 2005. 
                td Esta busca el uso y manejo adecuado de los residuos peligrosos, los cuales son considerados como fuentes de riesgo para el medio ambiente y la salud. 
                td.text-center
                  a.boton.color-primario.texto-blanco(href="http://www.ideam.gov.co/documents/51310/526371/POLITICA+AMBIENTAL+PARA+LA+GESTION+INTEGRAL+DE+RESPEL.pdf/fb42059d-77ec-423b-8306-960dee6bb9c6" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download
              tr
                td Resolución 668 de 2016. 
                td Por la cual se reglamenta el uso racional de bolsas plásticas y se adoptan otras disposiciones.
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://www.minambiente.gov.co/documento-normativa/resolucion-668-de-2016/" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download
              tr
                td Ley 1333 de 2009. 
                td Por la cual se establece el procedimiento sancionatorio ambiental y se dictan otras disposiciones.
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=36879" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download
              
              tr
                td Resolución 2087 de 2014. 
                td Por la cual se adopta el Protocolo para el monitoreo, control y vigilancia de olores ofensivos.
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://fenavi.org/wp-content/uploads/2018/05/Resoluci%C3%B3n-2087-de-2014-Protocolo-Monitoreo-control-y-Vigilancia-de-Olores-Ofensivos-1.pdf" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download

              tr
                td Resolución 1207 de 2014. 
                td Por la cual se adoptan disposiciones relacionadas con el uso de aguas residuales tratadas. 
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://fenavi.org/wp-content/uploads/2018/05/Resoluci%C3%B3n_1207_2014-Reuso-aguas-tratadas-1.pdf" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download

              tr
                td Ley 1672 de 2013. 
                td Por la cual se establecen los lineamientos para la adopción de una política pública de gestión integral de residuos de aparatos eléctricos y electrónicos (RAEE), y se dictan otras disposiciones.  
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://fenavi.org/wp-content/uploads/2018/05/ley_1672_2013-1.pdf" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download

              tr
                td Resolución ICA 3650 de 2014. 
                td Por medio de la cual se establecen los requisitos para el registro como productor de material genético aviar y expedición de licencias de venta de material genético aviar.
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://www.ica.gov.co/getattachment/3c2f3642-85a5-4622-91b5-5a31597c2cb4/2014R3-(1).aspx" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download

              tr
                td Resolución ICA 3652 de 2014.  
                td Por medio de la cual se establecen los requisitos para la certificación de granjas avícolas bioseguras de engorde y se dictan otras disposiciones.
                td.text-center
                  a.boton.color-primario.texto-blanco(href="https://www.ica.gov.co/getattachment/124802ad-c49c-470d-809e-a9ce5ad3db76/2014R3652.aspx" target="_blank")
                    span Descargar PDF
                    i.fas.fa-download

              tr
                td Resolución ICA 3651 de 2014.   
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
