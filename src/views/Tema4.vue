<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Plan de mejora 

    .d-flex.flex-wrap.mb-5
      .col-xl-7.pe-xl-5.d-flex.flex-wrap.align-items-center.order-2.order-xl-1
        .cajon.color-primario.p-4.d-flex.flex-wrap(data-aos="fade-right")
          .col-md-11.ps-lg-4
            p La norma ISO 14001 llamada “Sistemas de gestión ambiental”, es un plan operativo diseñado para que las empresas u organizaciones implementen buenas prácticas ambientales y se certifiquen en el manejo responsable de todo material derivado de sus quehaceres, con lo cual se disminuye la afectación del ambiente. Las instituciones que lo hagan estarán demostrando que están llevando a cabo sus actividades productivas de acuerdo a los estándares que se han fijado en cuanto a materia medioambiental promoviendo la protección del medio natural, la prevención de la contaminación y es el estándar internacional.
      img.mb-4.mb-xl-0.col-xl-5.mx-auto.order-1.order-xl-2(src="@/assets/curso/temas/tema4/img-1.png" data-aos="fade-left" style="max-width: 500px")

    .row.justify-content-center.align-items-center.mb-4
      .col-md-10.col-lg-9.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/tema1/decorador-2.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4 Sistema de gestión ambiental  
                  p.text-small Para más información consultar la norma ISO 14001 del 2015 puede consultar el siguiente documento. 
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.ramajudicial.gov.co/documents/8957139/22744716/NORMA+14001+%281%29%281%29.pdf/c26b5d90-20ba-4af0-8e4a-3ae1c45315e2" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    Separador 

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_1_1 4.1 ¿Qué es la segregación? 

    .col-12.d-flex.flex-wrap.align-items-center.p-2.mb-4
      .col-12.col-md-3.col-lg-1
        img.mb-4.mb-md-0.mx-auto(src="@/assets/curso/temas/tema4/decorador-1.svg" data-aos="fade-right" style="max-width: 100px")
      p.col.mb-0.col-md-9.col-lg-11.ps-lg-4(data-aos="fade-left") Es el proceso en el que se separa de forma correcta y eficiente los distintos productos desechados. De este modo, se contribuye activamente a economías más sostenibles y limpias capaces de reducir los vertidos y aprovechar los materiales mediante la reducción, reutilización y reciclaje. Esta actividad tiene como objetivo principal pasar de un consumo lineal a uno circular. 

    Separador

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_1_1 4.2 Separación en la fuente
    
    .col-12.d-flex.flex-wrap.align-items-center.p-2.mb-4
      .col-12.col-md-3.col-lg-1
        img.mb-4.mb-md-0.mx-auto(src="@/assets/curso/temas/tema4/decorador-2.svg" data-aos="fade-right" style="max-width: 100px")
      p.col.mb-0.col-md-9.col-lg-11.ps-lg-4(data-aos="fade-left") La separación en la fuente es la actividad que permite seleccionar y almacenar los diferentes residuos sólidos en su lugar de origen, para facilitar su posterior manejo y aprovechamiento; es un mecanismo efectivo para mitigar el impacto negativo de los residuos sólidos en el medio ambiente y prolongar la vida útil de los rellenos sanitarios, pero para esto, se necesita que esta actividad se convierta en un hábito cotidiano de todos los hogares y demás grupos de la sociedad.

    Separador
    
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_1_1 4.3 Reducir, reutilizar y reciclar 

    p.mb-5 A esto se le denomina la regla de las tres erres (3R) y es una estrategia que busca cuidar el medio ambiente al reducir la cantidad de residuos generados diariamente. Estas tres erres promueven la reducción de basura, el ahorro y un consumo más consciente. A continuación, se detalla el significado de las 3R:
    
    .row.justify-content-center(data-aos="fade-right")
      .col-lg-10
        figure.desktop.d-none.d-sm-block.d-sm-none.d-lg-block.d-none.d-md-block
          img.pb-5(src="@/assets/curso//temas/tema4/cuadro-1.svg" data-aos="zoom-in-up" alt="")
        figure.movil.mt-0  
          .row.justify-content-center.d-lg-none.d-md-none  
            img.pb-5(src="@/assets/curso/temas/tema4/cuadro-2.svg" data-aos="zoom-in-up" alt="")

    p.mb-5 Estas tres acciones combinadas buscan minimizar el impacto ambiental de nuestras acciones diarias y promover un estilo de vida más sostenible.

    .tarjeta.color-primario.p-3.mt-3.caja_flotante_azul.col-md-9.m-auto.mb-5(data-aos="fade-down")
      .row.justify-content-around.align-items-center
        .col-4.col-sm-2.col-lg-2
          img.p-4.imagen_flotante_animada(src="@/assets/curso/temas/tema4/decorador-3.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              .h4(style="color: #FFFF") 3R 
              p(style="color: #FFFF") Para profundizar sus conocimientos acerca del tema sobre reducir, reutilizar y reciclar, puede revisar el video llamado “3R de la Ecología”.
            .col-sm-auto
              a.boton.boton--b.color-acento-botones(href="https://youtu.be/rRCZzrMjiY0" target="_blank")
                span(style="color: #12263F !important;") Ir al sitio web
                i.fas.fa-link(style="color: #12263F !important;")

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_1_1 4.4 Tipos de rotulado y características de almacenamiento 

    .row.mb-3.justify-content-center.align-items-center
      .col-12.col-md-5.mb-5.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema4/img-3.png', alt='')  
      .col-12.col-md-7.mb-lg-0(data-aos="fade-left")
        p Tal como se ha abordado previamente, la adopción de las 3R es fundamental. En relación a ello, el Ministerio de la Protección Social destaca que los recipientes utilizados para almacenar residuos sólidos deben cumplir con al menos las siguientes cualidades:
        ul.lista-ul
          li 
            i.lista-ul__vineta
            | Material resistente y rígido: los recipientes deben estar fabricados con un material sólido y fuerte, que garantice durabilidad y evite roturas.
          li 
            i.lista-ul__vineta
            | Impermeabilidad: es crucial que el material sea impermeable para prevenir filtraciones de líquidos o humedad que puedan afectar su contenido y causar contaminación.
          li  
            i.lista-ul__vineta
            | Resistencia a golpes: los recipientes deben ser capaces de soportar impactos sin dañarse, asegurando así su funcionalidad a largo plazo.
          li  
            i.lista-ul__vineta
            | Facilidad de limpieza y desinfección: deben ser diseñados de manera que su limpieza y desinfección sean sencillas, evitando la acumulación de residuos y posibles focos de contaminación.
          li  
            i.lista-ul__vineta
            | Livianos y tamaño adecuado: deben ser lo suficientemente livianos para su manipulación y contar con un tamaño que permita almacenar los residuos entre las recolecciones programadas.
        p El cumplimiento de estas características garantiza un manejo adecuado de los residuos sólidos, contribuyendo a mantener un ambiente limpio y saludable.

    p Cuando se emplean bolsas desechables, es importante que estas sean lo suficientemente resistentes para soportar el peso de los residuos y su manipulación. Deben tener un calibre que asegure que no haya derrames durante la recolección, almacenamiento y disposición final de los residuos que contengan.
    p En cuanto al lugar de almacenamiento de los residuos, debe cumplir con al menos las siguientes características:
    ul.lista-ul.mb-3
      li 
        i.lista-ul__vineta
        | Ubicación adecuada: debe estar ubicado lejos de áreas de bodega, almacenamiento y preparación de alimentos, galpones y zonas administrativas.
      li 
        i.lista-ul__vineta
        | Facilidad de limpieza: debe permitir la realización de actividades de limpieza y desinfección, evitando la acumulación de suciedad y posibles focos de contaminación.
      li  
        i.lista-ul__vineta
        | Accesibilidad: debe ser de fácil acceso para los vehículos recolectores, facilitando la recolección de los residuos.
      li  
        i.lista-ul__vineta
        | Residuos sólidos exclusivamente: solamente se deben almacenar residuos sólidos en este lugar.
      li  
        i.lista-ul__vineta
        | Dirección clara: debe estar correctamente señalizado y direccionado para su identificación.
      li  
        i.lista-ul__vineta
        | Recipientes adecuados: los contenedores o recolectores utilizados deben ser impermeables y contar con tapa para evitar el ingreso de plagas y la humedad de su contenido.
    p.mb-5 Cumplir con estas directrices asegura un manejo eficiente y seguro de los residuos sólidos, reduciendo riesgos y promoviendo un entorno limpio y saludable. A continuación, se describen algunos tipos de productos sólidos que, según su naturaleza, pueden clasificarse tal como se indica en la siguiente infografía interactiva.

    ImagenInfografica.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/temas/tema4/img-4.svg', alt='Texto que describa la imagen')

      .tarjeta.color-primario.p-3(x="61.5%" y="27%" numero="1")
        .h5.mb-2 Productos reciclables
        p Son productos que podrán ser reutilizados en el futuro, siempre y cuando se haya realizado una correcta segregación de residuos. Es el caso de los productos que se utilizan a diario en las empresas y hogares, tales como:
        .col-sm.mb-5.mb-sm-0
          ul.lista-ul--color
            li 
              i.fas.fa-check
              | Papel y cartón (contenedor azul).
            li 
              i.fas.fa-check
              | Vidrio (contenedor verde).
            li 
              i.fas.fa-check
              | Plásticos y envases (contenedor amarillo).
            li 
              i.fas.fa-check
              | Los metales.

      .tarjeta.color-primario.p-3(x="50%" y="92%" numero="2")
        .h5.mb-2 Productos biodegradables
        p Son aquellos productos que se pueden descomponer siguiendo el proceso lógico y natural de la propia naturaleza.
        p Es el caso de productos como: restos de comida, cáscaras de fruta, restos de jardinería, y forraje para animales.
        p Este tipo de productos se pueden convertir, por ejemplo, en productos naturales como el compost.

      .tarjeta.color-primario.p-3(x="23.5%" y="55.5%" numero="3")
        .h5.mb-2 Baterías y productos electrónicos
        p Es de vital importancia separar este tipo de residuos de otros, ya que su alto grado de contaminación representa una grave amenaza para el equilibrio del entorno. Es crucial recordar que estos deben ser separados y depositados en lugares adecuados para su tratamiento.
        p Cada vez es más común encontrar puntos de recogida específicos en las ciudades, diseñados para desechar este tipo de materiales, evitando que sean procesados junto con otros productos.

    p.mb-5 Como se puede apreciar, es de vital importancia considerar diversos elementos al gestionar empresas avícolas en Colombia, dado que el cumplimiento de estos estándares, cuando se determina en buenas prácticas aplicadas diariamente, genera productos de calidad que se comercializan tanto a nivel nacional como internacional.

    .tarjeta.color-primario.p-3.mt-3.caja_flotante_azul.col-md-9.m-auto.mb-5(data-aos="fade-down")
      .row.justify-content-around.align-items-center
        .col-4.col-sm-2.col-lg-2
          img.p-4.imagen_flotante_animada(src="@/assets/curso/temas/tema4/decorador-4.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              .h4(style="color: #FFFF") Clasificación de residuos sólidos 
              p(style="color: #FFFF") Para ampliar conocimientos sobre la nomenclatura para la clasificación por colores puede ver el video “Clasificación de los residuos sólidos 2019”.
            .col-sm-auto
              a.boton.boton--b.color-acento-botones(href="https://www.youtube.com/watch?v=J2lcgWUqS98" target="_blank")
                span(style="color: #12263F !important;") Ir al sitio web
                i.fas.fa-link(style="color: #12263F !important;")

    Separador 

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_1_1 4.5 Clases de rutas

    .row.justify-content-center.align-items-center
      .col-md-7.mb-4.mb-md-0(data-aos="fade-down-left")
        p Las rutas de los residuos deben generarse teniendo en cuenta su clasificación, almacenamiento y transporte, para que de forma coordinada se pueda hacer la disposición final. Además, debe llevarse un registro detallado del material que sale y el tipo de disposición, así como de la frecuencia con que sale, incluyendo los horarios.
        p Dentro de las instalaciones debe encontrarse un plano en donde se encuentren marcadas y discriminadas las rutas que se pueden usar, las cuales debe conocer y seguir el personal estrictamente, estas también deben estar direccionadas en físico dentro del plantel. Finalmente, a cada una se le debe asignar un grupo de responsables quienes velarán por que se cumpla la labor correctamente.
        p El cumplimiento de estas rutas es muy importante, puesto que, si se hace un mal manejo, se pueden producir graves afectaciones ambientales y sanitarias a los procesos productivos y a la salud humana.
      .col-md-5.mb-4.mb-md-0(data-aos="fade-down")
        figure
          img(src='@/assets/curso/temas/tema4/img-5.png', alt='')





</template>

<script>
export default {
  name: 'Tema4',
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
