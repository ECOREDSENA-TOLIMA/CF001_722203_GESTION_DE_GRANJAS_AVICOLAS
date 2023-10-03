<template lang="pug">
.curso-main-container.pb-3.tema5
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Plan de Gestión Integral de Residuos Sólidos (PGIRS)

    .cajon-b.color-primario.p-3.mb-5
      p.mb-0 Para obtener una visión general de qué es un plan de gestión de residuos sólidos y cómo se aplica en la vida cotidiana, te invito a ver el video titulado "Planes de Gestión Integral de Residuos Sólidos", el cual se encuentra a continuación.

    .tarjeta.color-primario.p-3.mt-3.caja_flotante_azul.col-12.col-lg-10.m-auto.mb-5(data-aos="fade-down")
      .row.justify-content-around.align-items-center
        .col-4.col-sm-3.col-lg-2
          img.p-md-4.p-sm-0.imagen_flotante_animada(src="@/assets/curso/temas/tema4/decorador-4.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              .h4(style="color: #FFFF") Planes de gestión integral de residuos sólidos  
              p(style="color: #FFFF") Para ampliar su conocimiento acerca del Plan de Gestión Integral de Residuos Sólidos puede acceder al siguiente video. 
            .col-sm-auto
              a.boton.boton--b.color-acento-botones(href="https://www.youtube.com/watch?v=GPIcH8RAJTk" target="_blank")
                span(style="color: #12263F !important;") Ver video
                i.fas.fa-file-video(style="color: #12263F !important;")

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema5/img-1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La disposición y manejo adecuado de estos recursos, tales como: la gallinaza, la cáscara de huevo, la mortalidad y las bandejas de huevo, entre otros; se considera de mucha importancia, ya que, estas contribuyen a la sostenibilidad y eficiencia de la producción, puesto que, permiten que se garantice la aplicación de las buenas prácticas, la bioseguridad y las producciones limpias en el desarrollo de las actividades diarias avícolas, garantizando que no se generen molestias en el entorno por generación de olores y plagas. 
          br
          br
          | De acuerdo con lo establecido en el Decreto 1713 (2002), un residuo sólido es cualquier objeto, material, sustancia o elemento sólido que resulta del consumo o uso de un bien en actividades domésticas, industriales, comerciales, institucionales y de servicios que el generador abandona, rechaza o entrega, y que es susceptible de aprovechamiento o transformación en un nuevo bien, con valor económico o de disposición final. De forma general estos, pueden dividirse en tres grupos, para conocerlos revise la siguiente información: 

    .row.mb-5(data-aos="fade-right")
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar1
          img(src='@/assets/curso/temas/tema5/decorador-1.svg' alt='')
          .tarjeta.tarjeta--azul2
            .p-4
              h4.text-center Residuo sólido aprovechable
              p.text-center Es cualquier material, objeto, sustancia o elemento sólido que no tiene valor de uso directo o indirecto para quien lo genere, pero que es susceptible de incorporación a un proceso productivo. 
              p.text-center Entre los aprovechables, se encuentran: papel blanco usado por ambas caras, papel de archivo, cartón, papel cartón y plastificado, papel periódico, revistas, plástico, vidrio, madera y metal, entre otros.

      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar1
          img(src='@/assets/curso/temas/tema5/decorador-2.svg' alt='')
          .tarjeta.tarjeta--azul3
            .p-4
              h4.text-center Residuo sólido no aprovechable
              p.text-center Es todo material o sustancia sólida o semisólida de origen orgánico e inorgánico, putrescible o no, que proviene de actividades domésticas, industriales, comerciales, institucionales y de servicios que no ofrece alguna posibilidad de aprovechamiento, reutilización o reincorporación en un proceso productivo.
              p.text-center Son aquellos, que no tienen algún valor comercial, requieren tratamiento y disposición final que genera costo para su disposición.

      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar1
          img(src='@/assets/curso/temas/tema5/decorador-3.svg' alt='')
          .tarjeta.tarjeta--azul4
            .p-4
              h4.text-center Residuos peligrosos
              p.text-center Estos están definidos como aquellos que, por sus características infecciosas, tóxicas, explosivas, corrosivas, inflamables, volátiles, combustibles, radiactivas o reactivas puedan causar riesgo a la salud humana o deteriorar la calidad ambiental hasta niveles que causen riesgo a la salud humana.
              p.text-center Son aquellos que sin serlo en su forma original se transforman por procesos naturales en residuos peligrosos. Así mismo, se consideran peligrosos los siguientes elementos: los envases, empaques y embalajes que hayan estado en contacto con ellos.

    p.mb-5 Todos los residuos sólidos generados durante las diferentes actividades humanas y económicas, deben recibir una disposición final adecuada, con el fin de evitar la contaminación ambiental y contribuir con la conservación de los recursos naturales. (Decreto 1713, 2002)

    .row.justify-content-center.align-items-center.mb-5
      .col-md-10.col-lg-9.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/tema1/decorador-2.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4 Guía rápida de alternativas para el manejo de residuos sólidos ordinarios en la granja
                  p.text-small Para profundizar sobre el manejo de residuos sólidos puede revisar la “Guía rápida de alternativas para el manejo de residuos sólidos ordinarios en la granja” generado por la Federación Nacional de Avicultores - FENAVI.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://fenavi.org/wp-content/uploads/2018/05/Guia_Rapida_Ambiental_Manejo_Residuos_Solidos.pdf" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    .col-xl-10.mx-auto.mb-5
      .titulo-sexto.color-primario(data-aos="fade-right")
        h5 Figura 1.
        span <em>Clasificación de los residuos sólidos en el sector avícola</em>
      img.d-md-block.mb-5(src="@/assets/curso/temas/tema5/img-2.svg" data-aos="fade-left" alt="Figura 1. Muestra la clasificación de los residuos sólidos en el sector avícola, divididos en residuos orgánicos, residuos convencionales no peligrosos y residuos peligrosos.")
      
    .tarjeta.color-primario.p-3.mt-3.caja_flotante_azul.col-12.col-lg-10.m-auto.mb-5(data-aos="fade-down")
      .row.justify-content-around.align-items-center
        .col-4.col-sm-3.col-lg-2
          img.p-md-4.p-sm-0.imagen_flotante_animada(src="@/assets/curso/temas/tema4/decorador-4.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              .h4(style="color: #FFFF") Manejo de residuos en granjas avícolas  
              p(style="color: #FFFF") Para conocer más acerca del manejo de residuos sólidos en una granja puede ver el video “Manejo y disposición de residuos sólidos en granjas avícolas”.
            .col-sm-auto
              a.boton.boton--b.color-acento-botones(href="https://www.youtube.com/watch?v=3fzop2lQ7Ps" target="_blank")
                span(style="color: #12263F !important;") Ver video
                i.fas.fa-file-video(style="color: #12263F !important;")

    .row.justify-content-center.align-items-center
      .col-md-7.mb-4.mb-md-0(data-aos="fade-down-left")
        p Los residuos más representativos dentro del proceso de producción avícola, tanto para carne como para huevo, son: los orgánicos principalmente la gallinaza y la mortalidad, esto por su cantidad, volumen y características. 
        p Por otro lado, su inadecuada disposición o mal manejo, puede generar aumento de olores ofensivos, propagación de vectores (mosca y roedores), incremento de problemas sanitarios por la propagación de patógenos presentes en estos residuos y aumento de problemas   en la salud de la comunidad, además del incumplimiento de la normatividad existente en términos de sanidad animal (FENAVI - FONAV, 2018).
        p Para ello se han adoptado dos procesos con el fin de mitigar y controlar los efectos de estos dos residuos.
      .col-md-5.mb-4.mb-md-0(data-aos="fade-down")
        figure
          img(src='@/assets/curso/temas/tema5/img-3.png', alt='')

    Separador 
    #t_5_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 5.1 Sanitización de la gallinaza o pollinaza 

    .row.mb-5.justify-content-center.align-items-center
      .col-12.col-md-5.mb-5.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema5/img-4.png', alt='')  
      .col-12.col-md-7.mb-lg-0(data-aos="fade-left")
        p De acuerdo a la resolución ICA 30292 (2007), la sanitización es una serie de procesos físicos y/o químicos y/o biológicos, a los cuales debe ser sometida la gallinaza y pollinaza, cuyo propósito es reducir la presencia de microorganismos patógenos en estos subproductos, antes de ser retirados de la granja o reutilizados en la misma granja.
        p Como parte de su aprendizaje se hace necesario conocer ¿Cómo se sanitiza la cama? Para sanitizar la gallinaza se requiere que todo el material esté expuesto y que conserve la misma temperatura, pero este proceso debe ser controlado y por tiempo mínimo definido específico.
        p A continuación, se especifican los pasos a seguir para hacer una correcta sanitización de la gallinaza o pollinaza.

    //- .col-xl-12.mx-auto
    //-   .titulo-sexto.color-primario(data-aos="fade-right")
    //-     h5 Figura 2.
    //-     span <em>Correcta sanitización de la gallinaza o pollinaza.</em>

    .row.justify-content-center.align-items-center
      .col-md-11.col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img.px-4
            img(src='@/assets/curso/temas/tema5/numero-1.svg' alt='')
          .tarjeta.tarjeta--custom
            .p-4
              h4 Homogenizar cama
              p Flamear y picar para eliminar material empastado.
      .col-md-11.col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img.px-4
            img(src='@/assets/curso/temas/tema5/numero-2.svg' alt='')
          .tarjeta.tarjeta--custom
            .p-4
              h4 Humedecer la cama y hacer pilas 
              p Moviendo el material hacia el centro del galpón. Se debe verificar la humedad alcanzada realizando la prueba de puño (al empuñar una cantidad de material este debe ser compacto). El alto de la pila debe ser la mitad de ancho de la base y no menor a 1,50 metros.
      .col-md-11.col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img.px-4
            img(src='@/assets/curso/temas/tema5/numero-3.svg' alt='')
          .tarjeta.tarjeta--custom
            .p-4
              h4 Cubrir con plásticos
              p Al terminar el apilamiento de toda la cama se debe cubrir con un plástico de calibre grueso para contribuir con el aumento de la temperatura, por otro lado, a cada pila se le debe hacer un registro (llevar seguimiento y control de la temperatura), para lo cual deben identificarse independientemente a través de numeración.
      .col-md-11.col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img.px-4
            img(src='@/assets/curso/temas/tema5/numero-4.svg' alt='')
          .tarjeta.tarjeta--custom
            .p-4
              h4 Seguimiento y control de la temperatura en las pilas
              p Diariamente se debe realizar la medición de la temperatura y llevar los registros correspondientes, cuando se alcancen los 52 - 55°C se dejan reposar las pilas durante dos días, es decir se restringe el movimiento.
      .col-md-11.col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img.px-4
            img(src='@/assets/curso/temas/tema5/numero-5.svg' alt='')
          .tarjeta.tarjeta--custom
            .p-4
              h4 Enfriamiento de retiro del material 
              p Tras el periodo de reposo, se extienden las pilas para que se enfríen y se empacan para sacarlas del galpón. 

    Separador
    #t_5_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 5.2 Compostaje de mortalidad

    .d-flex.flex-wrap.mb-5
      .col-xl-8.pe-xl-4.d-flex.flex-wrap.align-items-center.order-2.order-xl-1
        .color-primario.p-4.d-flex.flex-wrap(data-aos="fade-right" style="background-color:#FFDBDB")
          .col-md-11.ps-lg-4
            p.mb-0 La disposición de las mortalidades que acompañan al proceso normal de producción avícola, deben realizarse regularmente dentro de las primeras 24 a 48 horas de acontecida la muerte de las aves, en términos prácticos, al menos una vez al día y con métodos que impidan la diseminación de microorganismos patógenos hacia las aves sanas, así como, la proliferación de fauna nociva. 
            p.mb-0 El compostaje, es una alternativa que le posibilita al productor transformar de manera segura usar los residuos orgánicos y obtener con ellos un producto más simple y estable. En este proceso la materia orgánica que conforma los organismos vivos se transforma en sustancias más simples. Se desarrolla en presencia de oxígeno y lo llevan adelante microorganismos (bacterias y hongos) que se encuentran en el ambiente, por lo cual, es un proceso natural.
              br
              br
              | Durante el proceso se desarrollan las siguientes etapas:
      img.mb-4.mb-xl-0.col-xl-4.mx-auto.order-1.order-xl-2(src="@/assets/curso/temas/tema5/img-5.png" data-aos="fade-left" style="max-width: 400px")

    //- .col-xl-12.mx-auto
    //-   .titulo-sexto.color-primario(data-aos="fade-right")
    //-     h5 Figura 3.
    //-     span <em>Etapas del compostaje.</em>

    PasosA.color-acento-contenido.mb-5(tipo="n" data-aos="fade-right")
      div
        h3 1. Etapa mesofílica
        p La mezcla alcanza temperaturas de hasta 40°C.

      div
        h3 2. Etapa termofílica o de higienización
        p La mezcla alcanza temperaturas que superan los 60°C, por lo cual se produce la muerte de los microorganismos patógenos (causantes de enfermedades).

      div
        h3 3. Etapa de enfriamiento o mesófila II
        p La temperatura comienza a descender hasta igualar la ambiental.

      div
        h3 4. Etapa de maduración
        p La mezcla se encuentra estable.

    p Para compostar, se debe contar con un espacio con un área mínima requerida del 5 % de la capacidad de encasetamiento y un área adicional para manejo de contingencias.
    p.mb-5 Existen dos métodos generales de compostaje aplicables a la mortalidad:

    .col-xl-10.mx-auto.mb-5
      .titulo-sexto.color-primario(data-aos="fade-right")
        h5 Figura 2.
        span <em>Métodos de compostaje.</em>
      img.d-md-block.mb-5(src="@/assets/curso/temas/tema5/img-6.svg" data-aos="fade-left" alt="En la figura 2 se muestran los métodos de compostaje.")

    .col-12.d-flex.flex-wrap.align-items-center.p-2.mb-5
      .col-12.col-md-3.col-lg-1
        img.mb-4.mb-md-0.mx-auto(src="@/assets/curso/temas/tema5/decorador-4.svg" data-aos="fade-right" style="max-width: 100px")
      p.col.mb-0.col-md-9.col-lg-11.ps-lg-4(data-aos="fade-left") El principio es el mismo, sólo que el método de encajonamiento requiere un poco más de inversión y mano de obra, pero permite un mejor control sobre los microorganismos patógenos, lo cual lo hace más eficiente. 
        br
        br
        | Por lo cual, este método se explicará más detalladamente a continuación.

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_1_1 Compostera y cajones      

    p La compostera es la infraestructura donde se ubica el compost, esta puede ser un kiosco o caseta, la cual debe contar con ciertas especificaciones que se mencionan más adelante; y los cajones como ya se había dicho son los contenedores en donde se almacenará y tratará el compost.  Enseguida se conocerán algunas exigencias para su diseño y construcción: 

    .cajon-b.color-acento-contenido.p-3.mb-5
      p.mb-0 Para hacer el compost se hace necesario contar con varios elementos indispensables, los cuales son:

    .tarjeta.tarjeta--gris.p-4.mb-5
      PasosB.color-acento-contenido

        .row(titulo="La compostera")
          .col-md-12.col-ipad.mb-4.mb-md-0
            p Es una estructura que debe ubicarse en una zona lo suficientemente alejada de los galpones para evitar contaminación de cualquier tipo, ya sea, por el flujo del personal o por las corrientes de aire; además se debe evitar la obstaculización por arbusto, paredes u otros elementos.

        .row(titulo="Ubicación")
          .col-md-12.col-ipad.mb-4.mb-md-0
            p No debe estar cerca de fuentes del agua como ríos, nacimientos, quebradas, arroyos, lagunas, ni en una pendiente.

        .row(titulo="Distribución")
          .col-md-12.col-ipad.mb-4.mb-md-0
            p Se debe elegir una distribución que evite el humedecimiento y que permita la aireación del material, así como el acopio de los productos biológicos (pollinaza o gallinaza y mortalidad) y de los elementos utilizados durante el proceso que faciliten la labor.

        .row(titulo="La compostera debe")
          .col-md-12.col-ipad.mb-4.mb-md-0
            p Contar con un  techo que cubra holgadamente el área efectiva de compostaje, con una altura de 2,2 a 2,5 m y un alero mínimo de 1,5 m para evitar que lluvias con viento humedezcan el compost.

        .row(titulo="Diseño")
          .col-md-12.col-ipad.mb-4.mb-md-0
            p Para optimizar el espacio de construcción se pueden diseñar dos líneas de cajones con cuatro compartimentos.

        .row(titulo="Terminado")
          .col-md-12.col-ipad.mb-4.mb-md-0
            p El piso debe ser impermeabilizado con broza o idealmente con una base de cemento para permitir mayor orden y evitar que la humedad proveniente del suelo dañe la mezcla, el borde debe ser de 2 a 3cm y una pendiente del 3 % desde el centro al exterior de la estructura.

        .row(titulo="Seguridad")
          .col-md-12.col-ipad.mb-4.mb-md-0
            p Además, con el fin de direccionar las aguas lluvias y evitar procesos de erosión, reboses o infiltraciones debe asegurarse la construcción de zanjas de desagüe o canales que permitan correr el agua.

        .row(titulo="Cajones")
          .col-md-12.col-ipad.mb-4.mb-md-0
            p Los Cajones  deben medir 1,5 m de largo X 1,5 m de ancho y 1,6 m de altura.
        
        .row(titulo="Funcionalidad")
          .col-md-12.col-ipad.mb-4.mb-md-0
            p Para facilitar la operatividad, cada cajón debe tener tres laterales fijos y uno desmontable. Este último debe permitir la entrada de una pala frontal para facilitar la tarea de extracción del compost o en el caso de que sea manual, y permitir al operario trabajar cómodamente.

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_1_1 ¿Cómo hacer el compostaje?

    .col-12.d-flex.flex-wrap.align-items-center.p-2.mb-5
      .col-12.col-md-3.col-lg-1
        img.mb-4.mb-md-0.mx-auto(src="@/assets/curso/temas/tema5/decorador-5.svg" data-aos="fade-right" style="max-width: 100px")
      p.col.mb-0.col-md-9.col-lg-11.ps-lg-4(data-aos="fade-left") Para hacer el compost es necesario hacer secuencialmente paso a paso el proceso, con el fin de que este sea exitoso, ya que se deben guardar las proporciones, los tiempos, las cantidades y las formas en las que van almacenados, mezclados y organizados cada uno de los componentes de este proceso, por eso hay que tener en cuenta la siguiente figura en la que se explica detalladamente la elaboración de este producto.

    .col-xl-10.mx-auto.mb-5
      .titulo-sexto.color-primario(data-aos="fade-right")
        h5 Figura 3.
        span <em>Proceso elaboración compostaje.</em>
      img.d-md-block.mb-5(src="@/assets/curso/temas/tema5/img-7.svg" data-aos="fade-left" alt="Figura 3. Proceso elaboración compostaje. Muestra los 4 pasos de manera detallada para la elaboración del compostaje.")

    p.mb-5 A continuación, se describe el procedimiento para hacer un correcto volteo del compost, la verificación de la humedad y el control del tiempo en las etapas que garanticen la calidad del producto, además de cómo realizar la clasificación del material que va a ser retirado y el que seguirá dentro del proceso, puede revisar la siguiente información: 

    .col-xl-10.mx-auto.mb-5
      .titulo-sexto.color-primario(data-aos="fade-right")
        h5 Figura 4.
        span <em>Correcto volteo del compost.</em>
      img.d-md-block.mb-5(src="@/assets/curso/temas/tema5/img-8.svg" data-aos="fade-left" alt="Figura 4. Métodos de compostaje como son el apilamiento y el encajonamiento.")

    .row.justify-content-center.align-items-center.mb-5
      .col-md-12.col-lg-10.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/tema4/decorador-4.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4 El compostaje  
                  p.text-small Para mayor comprensión sobre el compostaje dentro de las prácticas ambientales y sanitarias en la labor avícola, puede ver el video llamado “Compostaje de Mortalidad”.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://youtu.be/fd5mo5Pr1pQ" target="_blank")
                    span Ver video
                    i.fas.fa-file-video

    p.mb-5 Los procesos anteriores de manejo de la gallinaza y pollinaza, así como, el manejo adecuado de la mortalidad hacen parte fundamental en la normatividad ambiental y sanitaria dentro del ámbito avícola, por lo que los esfuerzos del gremio se han dirigido a hacer un documento para el sector que sirva como guía para todos los productores, profesionales y operarios que intervienen activamente en la actividad, esto se hace con el fin de prevenir, controlar y mitigar el impacto ambiental que pueda ocurrir a partir de la producción. Es así como nace la “Guía ambiental para el subsector avícola”, como un documento central y básico en el tema ambiental, que a continuación se abordará.

    .row.justify-content-center.align-items-center.mb-5
      .col-md-10.col-lg-9.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/tema1/decorador-2.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4 Guía ambiental para el subsector avícola  
                  p.text-small Para profundizar en las pautas del sector avícola puede leer “Guía ambiental para el subsector Avícola”
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://fenavi.org/wp-content/uploads/2018/05/GUIA_AMBIENTAL_SUBSECTOR_AVICOLA.pdf" target="_blank")
                    span Descargar
                    i.fas.fa-file-download


















</template>

<script>
export default {
  name: 'Tema5',
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
