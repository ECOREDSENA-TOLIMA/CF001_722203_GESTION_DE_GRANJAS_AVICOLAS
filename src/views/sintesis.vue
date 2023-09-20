<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    p.mb-5 El componente formativo de “Plan de manejo ambiental, monitoreo y valoración” en el ámbito de las granjas avícolas juega un papel fundamental para garantizar la sostenibilidad y el cuidado del medio ambiente. Este enfoque integral abarca la implementación de responsables en el manejo de insumos, la gestión adecuada de los residuos sólidos y la reducción de la huella de carbono. Además, implica el cumplimiento de la normativa ambiental vigente y la adopción de sistemas de gestión ambiental basados en la norma ISO 14001:2015. Mediante el monitoreo y la valoración ambiental, se evalúa el desempeño y se identifican oportunidades de mejora, contribuyendo así a una producción avícola más sostenible y responsable.

    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="Síntesis del componente formativo Plan de manejo ambiental, monitoreo y valoración en el ámbito de las granjas avícolas.")
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
