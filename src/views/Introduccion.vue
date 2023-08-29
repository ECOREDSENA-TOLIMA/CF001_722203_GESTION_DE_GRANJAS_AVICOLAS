<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-primario 
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .cajon.color-secundario.p-4.d-flex.flex-wrap.mb-5(data-aos="fade-right")
      .col-md-11.ps-lg-4
        p En el sector avícola, es de gran importancia establecer un plan de manejo ambiental, en donde se va a identificar la influencia que tienen las actividades productivas en el medio ambiente. El resultado de esta influencia se define como impactos ambientales y estos pueden ser positivos o negativos. Implementando las buenas prácticas de bioseguridad en la granja, podemos garantizar producciones más limpias, un bajo impacto ambiental y que no se vea afectada la rentabilidad de la empresa por las malas prácticas.      
        
    figure.mt-5.mb-5(data-aos="fade-right")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/ARP9nrTZ1ic" title="Plan de manejo ambiental, monitoreo y valoración" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)      
    

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
