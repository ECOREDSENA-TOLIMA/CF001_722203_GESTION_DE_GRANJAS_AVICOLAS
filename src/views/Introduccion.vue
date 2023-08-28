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
        p En Avicultura el plan ambiental hace parte fundamental de la producción, ya que tiene una influencia directa en este; de la misma forma puede observarse cómo: la sanitización de las camas, el tratamiento del agua, el manejo de residuos y la mortalidad impactan la calidad del aire. 
          br
          br
          | De igual manera, se puede identificar cómo productos de desecho y otros factores ambientales pueden afectar directa e indirectamente la rentabilidad y productividad de los galpones. Lo anterior, está correlacionado con la parte sanitaria y las buenas prácticas del sector para garantizar la bioseguridad y las producciones limpias. 

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
