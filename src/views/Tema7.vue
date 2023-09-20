<template lang="pug">
.curso-main-container.pb-3.tema5
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 7
      h1 Guía ambiental para el subsector avícola, FENAVI 2014             

    .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema7/img-1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Las guías ambientales se enmarcan dentro de la estrategia de generación de cultura de autogestión y autorregulación de la Política Nacional de producción y consumo sostenible emitida en el año 2010, la cual, integra: la Política Nacional de producción más limpia y el Plan Nacional de mercados verdes. 

    p.mb-5 Para profundizar en el aprendizaje puede acceder al siguiente documento: 

    .row.justify-content-center.align-items-center.mb-5
      .col-md-10.col-lg-9.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/tema1/decorador-2.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4 Política Nacional de Producción y consumo sostenible    
                  p.text-small Es una estrategia del estado colombiano para promover el mejoramiento ambiental, la transformación productiva y la competitividad empresarial.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.minambiente.gov.co/wp-content/uploads/2021/06/polit_nal_produccion_consumo_sostenible.pdf" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
  
    p Lo anterior, permite contribuir al mejoramiento productivo y ambiental de las granjas, incubadoras y plantas de beneficio del subsector avícola colombiano y ofrecer una herramienta de consulta permanente para este, a través de la adopción de medidas de prevención y control de los impactos ambientales que ayuden a prevenir, mitigar, controlar y compensar el deterioro que la producción avícola causa en el ambiente producto de sus actividades. 

    Separador 
    #t_7_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 7.1 Medidas de prevención, mitigación, control y compensación
  
    p.mb-5 Las medidas de mitigación ambiental tienen por finalidad evitar o disminuir los efectos adversos de un proyecto o actividad, cualquiera sea su fase de ejecución. Estas se expresarán en un plan, el cual deberá considerar, a lo menos, una de las siguientes medidas: 

    //- .col-xl-12.mx-auto
    //-   .titulo-sexto.color-primario(data-aos="fade-right")
    //-     h5 Figura 5.
    //-     span <em>Medidas de mitigación ambiental</em>

    .row.justify-content-center.align-items-center
      .col-md-11.col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img.px-4
            img(src='@/assets/curso/temas/tema7/decorador-1.svg' alt='AvatarTop')
          .tarjeta.tarjeta--custom
            .p-4
              p Las que impidan o eviten completamente el efecto adverso significativo, mediante la no ejecución de una obra o acción, o de alguna de sus partes. 
      .col-md-11.col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img.px-4
            img(src='@/assets/curso/temas/tema7/decorador-2.svg' alt='AvatarTop')
          .tarjeta.tarjeta--custom
            .p-4
              p Las que minimizan o disminuyen el efecto adverso significativo, mediante una adecuada limitación o reducción de la magnitud o duración de la obra o acción, o de alguna de sus partes, o a través de la implementación de medidas específicas.
      .col-md-11.col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img.px-4
            img(src='@/assets/curso/temas/tema7/decorador-3.svg' alt='AvatarTop')
          .tarjeta.tarjeta--custom
            .p-4
              p Las medidas de reparación y/o restauración tienen por finalidad reponer uno o más de los componentes o elementos del medio ambiente a una calidad similar a la que tenían con anterioridad al daño causado o, en caso de no ser ello posible, restablecer sus propiedades básicas. Dichas medidas se expresarán en un Plan de Medidas de Reparación y/o Restauración.
      .col-md-11.col-12(data-aos="fade-down")
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img.px-4
            img(src='@/assets/curso/temas/tema7/decorador-4.svg' alt='AvatarTop')
          .tarjeta.tarjeta--custom
            .p-4
              p Las medidas de compensación ambiental tienen por finalidad producir o generar un efecto positivo alternativo y equivalente a un efecto adverso identificado. Dichas medidas se expresarán en un Plan de Medidas de Compensación, el que incluirá el reemplazo o sustitución de los recursos naturales o elementos del medio ambiente afectados, por otros de similares características, clase, naturaleza y calidad.

    p Las dos últimas, sólo se llevarán a cabo en las áreas o lugares en que se presenten efectos adversos significativos que resulten de la ejecución o modificación de los planes de mitigación ambientales originales. 
    p  Por otro lado, las medidas de mitigación están hechas para disminuir y soportar los efectos e impactos en el ambiente productos de la actividad avícola y todo lo que ella conlleva, es decir, el uso del suelo, el agua, el aire, ya sea en la elaboración o adecuación de la infraestructura, el transporte, la generación de residuos y disposición de los mismos, y como tal el manejo de la producción por parte de administrativos, operarios, profesionales y demás personal que interactúa en el proceso. 
    p.mb-5 Si la aplicación y evaluación del impacto ambiental del proyecto o actividad se deducen eventuales situaciones de riesgo al medio ambiente, el titular del proyecto o actividad deberá proponer medidas de prevención de riesgos y de control de accidentes, las cuales se mencionan en la siguiente figura: 

    .row(data-aos="fade-right")
      .col-md-6.d-flex.align-items-stretch
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema7/ico1.svg' alt='')
          .tarjeta.tarjeta--azul2
            .p-4
              h4 Medidas de prevención de riesgo
              p.mb-0 Tienen por finalidad evitar que aparezcan efectos desfavorables en la población o en el medio ambiente.
      .col-md-6.d-flex.align-items-stretch
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema7/ico2.svg' alt='AvatarTop')
          .tarjeta.tarjeta--azul3
            .p-4
              h4 Medidas de control de accidentes
              p.mb-0 Tienen por finalidad permitir la intervención eficaz en los sucesos que alteren el desarrollo normal de un proyecto o actividad, en tanto puedan causar daños a la vida, a la salud humana o al medio ambiente.

    //- .col-xl-10.mx-auto.mb-5
    //-   .titulo-sexto.color-primario(data-aos="fade-right")
    //-     h5 Figura 6.
    //-     span <em>Medidas de prevención de riesgos y de control de accidentes.  </em>
    //-   img.d-md-block.mb-5(src="@/assets/curso/temas/tema7/img-2.svg" data-aos="fade-left")

    p Desde este punto de vista está considerado el tema de salud y seguridad en el trabajo, pero además el de las poblaciones aledañas a las producciones, las cuales pueden ser impactadas por las actividades de producción en las granjas avícolas, demostrando que no sólo es importante el factor ambiental en terreno y recursos aprovechables, sino también en las poblaciones, ya sean estas internas o externas. 
    p.mb-5 En este orden de ideas, entre los factores o recursos que se deben tener en cuenta cuando se habla de la parte ambiental de todo tipo de actividad, proyecto o producción, están: el recurso del suelo, el agua y el aire, principalmente, porque son los que, de acuerdo a su manejo pueden derivar en impactos ambientales significativos y por eso los abordaremos más detalladamente a continuación. 

    Separador
    #t_7_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 7.2 Recurso suelo 

    .row.mb-5.justify-content-center.align-items-center
      .col-12.col-md-5.mb-5.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema7/img-3.png', alt='')  
      .col-12.col-md-7.mb-lg-0(data-aos="fade-left")
        p Para el recurso suelo, la mayoría de contaminación producida se da por el inadecuado manejo de la pollinaza y gallinaza, ósea cuando son utilizadas como productos de abono y no se les ha realizado ningún tipo de proceso que cumpla con los parámetros que se establecen para los abonos o fertilizantes orgánicos (véase la Norma Técnica Colombiana para Productos Orgánicos Usados como Abonos o Fertilizantes: NTC 5167 / ICONTEC y las Resoluciones ICA 150 de 2003 y 0968 de 2010). 

    p.mb-5 Aplicar erróneamente abonos o fertilizantes orgánicos en el suelo pueden causar graves problemas a corto, mediano o largo plazo como se mencionará a continuación: 
    
    ImagenInfografica.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/temas/tema7/img-4.svg', alt='Texto que describa la imagen')

      .tarjeta.color-acento-contenido.p-3(x="18.5%" y="50%" numero="")
        h5(style="color: #000") Acción mecánica del estiércol
        ul.lista-ul.mb-3(style="color: #000")
          li(style="color: #000")
            i.lista-ul__vineta(style="color: #000")
            | Consiste en el taponamiento de los poros del suelo colmatándolo y limitando la capacidad de drenaje de las aguas lluvias, causando con frecuencia inundaciones.
          li(style="color: #000") 
            i.lista-ul__vineta(style="color: #000")
            | En un suelo anegado, el agua se convierte en un obstáculo para su oxigenación y da paso a la formación de zonas anaeróbicas donde prosperan microorganismos que producen gases como: el metano, el amoniaco y el gas sulfhídrico, alterando por completo la bioquímica del suelo.

      .tarjeta.color-acento-contenido.p-3(x="51%" y="50%" numero="")
        h5(style="color: #000") El exceso de nutrientes
        p(style="color: #000") Los microorganismos a través de su acción química en el suelo, convierten los componentes nitrogenados que se encuentran en la gallinaza o pollinaza en nitratos y nitritos, que normalmente ayudan a crecer el material vegetal, por lo que estos subproductos son utilizados con frecuencia para abonar, sin embargo, en concentraciones altas se convierten en componentes tóxicos afectando los suelos y aguas subterráneas.

      .tarjeta.color-acento-contenido.p-3(x="84.8%" y="50%" numero="")
        h5(style="color: #000") La acción biológica
        p(style="color: #000") A causa de las acciones anteriores, se puede presentar la diseminación de patógenos procedentes de la gallinaza o pollinaza, que se propaguen debido a un ambiente propicio (por ejemplo E. coli)

    p.mb-5 Adicionalmente hay que tener otras consideraciones, no menos importantes, tales como: si se trata de un residuo estabilizado y saneado, o no, revise la siguiente información para conocer la diferencia de cada uno.   

    //- .col-xl-10.mx-auto.mb-5
      //- .titulo-sexto.color-primario(data-aos="fade-right")
      //-   h5 Figura 5.
      //-   span <em>Tipos de residuos</em>
      //- img.d-md-block.mb-5(src="@/assets/curso/temas/tema7/img-5.svg" data-aos="fade-left" alt="En la figura 5 se muestran los tipos de residuos.")
    .row.mb-5(data-aos="fade-right")
      .col-md-6.col-12.mb-5.mb-lg-0.d-flex.align-items-stretch
        .tarjeta.tarjeta--azul2
          h4.text-center.mb-0.py-3.text-white(style="background-color:#03A4A4") Residuo fresco
          .p-4
            p.mb-0 Si es un residuo fresco la generación de olores puede presentarse como un problema, debido a que se incrementa la actividad microbiológica y con ella la rápida descomposición en el suelo, generando sustancias fito-tóxicas que elevan los contenidos de nitratos en material vegetal y origina lixiviados.
      .col-md-6.col-12.mb-5.mb-lg-0.d-flex.align-items-stretch
        .tarjeta.tarjeta--azul2
          h4.text-center.mb-0.py-3.text-white(style="background-color:#03A4A4") Residuo no saneado previamente
          .p-4
            p.mb-0 Si el residuo no ha sido previamente saneado, se favorecerá la diseminación de elementos patógenos propios de las producciones avícolas y que pueden estar presentes en las deyecciones de las aves, residuos de cascaras y otros residuos.

    p.mb-5 Por lo anterior, se debe llevar un adecuado plan de fertilización o acondicionamiento de suelos, el cual deberá contemplar las características fisicoquímicas y grado de estabilidad del producto que se piensa aplicar, así como las características del suelo (capacidad de drenaje, tipo de suelo, presencia de elementos mayores y menores) y las necesidades nutritivas de los cultivos a fertilizar. 

    .row.justify-content-center.align-items-center.mb-5
      .col-md-10.col-lg-9.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/tema1/decorador-2.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4 Política nacional para la gestión integral ambiental del suelo   
                  p.text-small Para profundizar en el manejo de los recursos del suelo puede revisar el documento: Política nacional para la gestión integral ambiental del suelo. 
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.andi.com.co/Uploads/Pol%C3%ADtica%20GIAS.pdf" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    p.mb-5 A continuación, se definen cuáles son las Medidas de prevención, mitigación y/o control para el uso del suelo:  

    .d-flex.flex-wrap
      .col-xl-12.pe-xl-4.d-flex.flex-wrap.align-items-center.order-2.order-xl-1
        .cajon.color-acento-contenido.p-4.d-flex.flex-wrap(data-aos="fade-right")
          .col-md-12.ps-lg-4
            ul.lista-ul.mb-3
              li 
                i.lista-ul__vineta
                | Implementación de prácticas de producción más limpia orientadas a la separación en la fuente y minimización de residuos sólidos.
              li 
                i.lista-ul__vineta
                | Capacitación y entrenamiento en la aplicación de Buenas Prácticas de Operación para el manejo de residuos sólidos y peligrosos. 
              li  
                i.lista-ul__vineta
                | Cumplir con las normas ambientales en lo referente al manejo y disposición final de residuos peligrosos.
              li  
                i.lista-ul__vineta
                | Los residuos peligrosos resultantes de la labor en las incubadoras tales como frascos plásticos o de vidrio, los cuales han estado en contacto directo o parcialmente con residuos biológicos, se les debe dar el siguiente tratamiento: sumergir en una solución de hipoclorito al 5 % durante 30 a 60 minutos y quebrar o despicar (vidrío) o cortar y rajar (plástico) según sea el caso, para evitar el uso ilegal o inadecuado de los envases.
              li  
                i.lista-ul__vineta
                | Es aconsejable almacenar los residuos sistemáticamente hasta lograr una cantidad considerable para ser recolectada por la empresa prestadora del servicio. No debe hacerse disposición final a través de la quema en ningún lugar de la producción.
              li  
                i.lista-ul__vineta
                | Las agujas de las jeringas y hojas de bisturí se deben almacenar en recipientes rígidos a prueba de perforaciones (guardianes), marcados con símbolo rojo que señale que contienen elementos corto-punzantes.
              li  
                i.lista-ul__vineta
                | En caso de presentarse derrames de combustible en las instalaciones de las incubadoras o plantas de beneficio, debe hacerse limpieza lo más pronto posible para facilitar la recuperación del combustible y minimizar los impactos al medio ambiente. 
              li  
                i.lista-ul__vineta
                | Como medida de seguridad los tanques de almacenamiento deben contar con diques para la retención del combustible en caso de derrames; así mismo, se aconseja como parte de las medidas de seguridad contar con extintores para el control de incendios.
              li  
                i.lista-ul__vineta
                | Los aceites usados se deben manejar de acuerdo a las recomendaciones suministradas por el fabricante o importador del lubricante, hasta finalizar su vida útil.
              li  
                i.lista-ul__vineta
                | Se debe realizar el cambio del aceite lubricante de los vehículos en establecimientos que cumplan con los requisitos de acopiador, establecidos en el Manual Técnico para el manejo de aceites lubricantes usados, expedido por el Ministerio de Ambiente, Vivienda y Desarrollo Territorial y las normas establecidas por la autoridad ambiental de la jurisdicción.
              li  
                i.lista-ul__vineta
                | En el uso de los plaguicidas se deben seguir las instrucciones de manejo seguro suministradas en la etiqueta del producto. Cuando se termina el producto, se debe realizar la práctica de triple lavado a los envases e inutilizarlos sin destruir la información de las etiquetas. Estos son considerados residuos post consumo de acuerdo al Decreto 4741 de 2005 y por lo tanto deben retornarse al mecanismo de devolución que el fabricante o importador haya establecido, de acuerdo con lo previsto en la Resolución 0693 de 2007.

    Separador 
    #t_7_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 7.3 Recurso agua 

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema7/img-2.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El agua es el recurso básico para garantizar la vida de todos los seres vivos del planeta, solo superado por el oxígeno. Se necesita el agua para cualquier actividad metabólica o fisiológica en el cuerpo o función de las hormonas y enzimas, ayuda a transportar los nutrientes y los desechos en el cuerpo y significativamente reduce la temperatura corporal especialmente en climas cálidos. 
          br
          br
          | Es un nutriente relativamente barato, muy disponible y de fácil acceso, al cual a veces no se le da la importancia que realmente tiene. Por eso, cualquier disminución en la disponibilidad, calidad o temperatura del agua definitivamente afecta al desempeño de las aves y afecta los procedimientos productivos en la industria.

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_1_1 Propiedades físico - químicas del agua

    .row.justify-content-center.align-items-center.mb-4
      .col-md-7.mb-4.mb-md-0(data-aos="fade-right")
        p Desde el punto de vista físico, las propiedades o características del agua son: su densidad  que  es de 1g/cm₃, amplio margen de temperaturas en fase líquida (0-100º C) ya que su punto de ebullición es a 100 °C a nivel del mar  y el de congelamiento es a 0ºC, constante dieléctrica elevada que permite que las disoluciones puedan conducir la electricidad y permite la disociación de la mayoría de las sales inorgánicas; elevado calor específico y calor de vaporización lo que causa que el calor liberado en reacciones bioquímicas exotérmicas sea fácilmente absorbido y/o eliminado con pequeña variación de la temperatura del individuo; y tensión superficial muy elevada que la hace pegajosa y elástica. 
      .col-md-4.mb-4.mb-md-0(data-aos="fade-down")
        figure
          img(src='@/assets/curso/temas/tema7/img-6.png', alt='')

    .row.mb-5.justify-content-center.align-items-center
      .col-12.col-md-4.mb-5.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema7/img-7.png', alt='')  
      .col-12.col-md-7.mb-lg-0(data-aos="fade-down")
        p En cuanto a las propiedades químicas del agua, las principales son: un átomo de oxígeno ligado a dos de hidrógeno lo cual es su fórmula química es H₂O, la molécula del agua tiene carga eléctrica positiva en un lado y negativa en el otro, propiedad que ocasiona que sus moléculas se unan entre sí; es dipolar, o sea,  las moléculas de agua se orientan en torno a las partículas polares o iónicas, formando una envoltura de solvatación lo que se traduce en una modificación de las propiedades de estas partículas; contiene minerales y nutrientes de gran valor; en su estado puro es de pH neutro (7) esto significa que no es ácida ni básica; reacciona con los óxidos ácidos, los óxidos básicos y el metal; forma hidratos al unirse con las sales.

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_1_1 Métodos del tratamiento del agua

    .d-flex.flex-wrap.mb-5
      .col-xl-8.pe-xl-4.d-flex.flex-wrap.align-items-center.order-2.order-xl-1(data-aos="fade-right")
        p En muchos lugares del mundo, el agua antes de llegar a los hogares y empresas donde se usa, recibe un tratamiento con diferentes métodos depurativos o de eliminación de algunos o todos los contaminantes que se encuentran en las aguas residuales, para que posteriormente, pueda ser utilizada.
        p Este proceso puede usar operaciones de distintos tipos (físico, químico, físico-químico o biológico), cuyo objetivo es la eliminación y/o reducción de la contaminación o de las características no deseables de las aguas.
        p Las aguas que son sometidas a tratamiento pueden provenir de diversas fuentes, ya sea de origen industrial, urbano o incluso de la propia naturaleza, dado que pueden contener compuestos químicos no adecuados para la salud. Además, el agua residual que se somete a tratamiento puede ser reutilizada para diversos fines, como el consumo humano, el riego de cultivos o en la industria, a veces llamada "agua virtual", o simplemente reintegrarse en corrientes de agua sin causar contaminación, lo que permite un ciclo de reciclaje constante.
      img.mb-4.mb-xl-0.col-xl-4.mx-auto.order-1.order-xl-2(src="@/assets/curso/temas/tema7/img-8.svg" data-aos="fade-right")

    .d-flex.flex-wrap.mb-5
      .col-xl-12.pe-xl-1.d-flex.flex-wrap.align-items-center.order-2.order-xl-1
        .cajon.color-primario.p-4.d-flex.flex-wrap(data-aos="fade-right")
          .col-md-12.ps-lg-4
            p El tratamiento de agua es cada vez más necesario debido a la escasez de este elemento de la naturaleza potable y a la creciente población mundial. Del total que hay en el planeta, tan solo un 2,5 % es agua dulce, y de esa cantidad tan solo el 0,4 % es apta para el consumo. El tratamiento de esta posee diferentes métodos que son empleados dependiendo de la utilización que se le quiera dar, los cuales se verán a continuación:

    .row.mb-5.justify-content-center.align-items-center.mb-5
      .col-12.col-md-5.mb-5.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema7/img-9.png', alt='')  
      .col-12.col-md-7.mb-lg-0(data-aos="fade-left")
        ul.lista-ul.mb-3
          li 
            i.lista-ul__vineta
            | Método de desbaste primario. 
          li 
            i.lista-ul__vineta
            | Filtrados por membranas (microfiltración, ultrafiltración, nanofiltración, ósmosis inversa).
          li 
            i.lista-ul__vineta
            | Acción del carbón activado.
          li 
            i.lista-ul__vineta
            | Método de descalcificación.
          li 
            i.lista-ul__vineta
            | Tratamiento con cloro.
          li 
            i.lista-ul__vineta
            | Tratamiento con ozono.
          li 
            i.lista-ul__vineta
            | Tratamiento de agua por medio de la luz ultravioleta.
          li 
            i.lista-ul__vineta
            | Método de desalinización.
          li 
            i.lista-ul__vineta
            | Destilación de agua.
          li 
            i.lista-ul__vineta
            | Planta Macrófitas.
          li 
            i.lista-ul__vineta
            | Aplicación de electricidad al agua residual.

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_1_1 Control ambiental del recurso hídrico en la industria avícola

    p En cualquier unidad productiva el consumo y manejo del recurso hídrico es uno de los puntos críticos. Porque las fuentes hídricas (superficiales y subterráneas) son afectadas principalmente por el vertimiento de aguas residuales provenientes de unidades productivas, en el caso de las granjas, esta situación se da por el uso ineficiente del agua en operaciones de lavado o por vertimiento directo, sin ningún tratamiento a las fuentes hídricas, así como, por arrastre de la gallinaza o pollinaza, si ésta se encuentra almacenada inadecuadamente.
    p.mb-5 A continuación, se mencionan las medidas de prevención, mitigación y/o control para el uso agua:

    .col-xl-11.mx-auto.mb-5(data-aos="fade-left")
      .fondo-color.p-4.d-flex.flex-wrap
        .cajon-b.color-acento-botones.p-3.mb-5
          .col-md-11.ps-lg-4
            .col-sm.mb-5.mb-sm-0
              ul.lista-ul.mb-3
                li 
                  i.lista-ul__vineta
                  | Es aconsejable el diseño y evaluación periódico de indicadores de consumo de agua para hacer seguimiento, control y generar alternativas de mejora. 
                li 
                  i.lista-ul__vineta
                  | Para la limpieza del galpón se recomienda realizar barridos en seco y lavados a presión.
                li 
                  i.lista-ul__vineta
                  | Instalar dispositivos ahorradores en bebederos, sanitarios, zonas de aspersión, lavamanos y duchas.
                li 
                  i.lista-ul__vineta
                  | Las tuberías y equipos deberán estar en buen estado para garantizar el uso eficiente del agua. 
                li 
                  i.lista-ul__vineta
                  | Los equipos y dispositivos (tuberías, grifos, bebederos) deberán tener una hoja de vida, donde se registren: lugar y fecha de compra, reparaciones, empresa prestadora del servicio técnico, entre otros. 
                li 
                  i.lista-ul__vineta
                  | La limpieza de los tanques de almacenamiento y las tuberías debe realizarse mínimo cada 2 meses (dependiendo de la dureza del agua), esto evitará que ocurran obstrucciones en los bebederos automáticos y reducirá la aparición de infecciones; la manera correcta de realizar la limpieza de los tanques es con agua a presión, cepillando sus paredes y aplicando desinfectante. En todo caso se debe evitar el desperdicio de agua, por lo que la limpieza debe hacerse cuando esté desocupado. 
                li 
                  i.lista-ul__vineta
                  | Para hacer un mejor control estadístico del consumo se recomienda hacer uso de los medidores. Se sugiere registrar dicho consumo al menos una vez por semana y considerar el número de aves, edad, actividad y operaciones de limpieza, entre otros. Adicionalmente, es importante contar con medidores exclusivos para el consumo doméstico, que registren no solamente el consumo de las familias que viven en las granjas, sino también el consumo que realizan los trabajadores en sus actividades. 
                li 
                  i.lista-ul__vineta
                  | Vincular al personal en los programas de capacitación y entrenamiento en la aplicación de prácticas, reforestación y conservación de cuencas hidrográficas. 
                li 
                  i.lista-ul__vineta
                  | Construcción de un comité para el seguimiento y control del recurso hídrico, el cual verificará la tendencia del consumo y el estado de las tuberías y los equipos.
      
    p.mb-5 Teniendo en cuenta lo anterior, y en adición pueden surgir otras prácticas que causen un uso ineficiente del recurso hídrico, esto puede deberse en la siguiente lista:

    .d-flex.flex-wrap.mb-5
      .col-xl-8.pe-xl-4.d-flex.flex-wrap.align-items-center.order-2.order-xl-1(data-aos="fade-right")
        ul.lista-ul--color
          li 
            i.fas.fa-check
            | No se registran ni controlan los consumos hídricos (auditoría al consumo y auditoría de seguimiento); poco empleo de medidores de consumo.
          li 
            i.fas.fa-check
            | En las operaciones de limpieza durante y después de la finalización del periodo no se hace barrido en seco o se hace mal, lo que causa incremento en el consumo de agua para las actividades de limpieza y lavado.
          li 
            i.fas.fa-check
            | El lavado de los galpones se realiza con mangueras sin dispositivos que aumenten la presión del agua.
          li 
            i.fas.fa-check
            | Las mangueras de lavado no cuentan con un dispositivo de cierre (pistola) que permita controlar la salida de agua. 
          li 
            i.fas.fa-check
            | Los sistemas que llevan el agua hacia las áreas operativas, administrativas y domésticas no se encuentran separadas. No se tienen separadas las redes de aguas lluvias y residuales lo que causa limitaciones en el aprovechamiento y uso de estas dentro del proceso productivo.
          li 
            i.fas.fa-check
            | Tuberías de conducción de agua y sistemas de almacenamiento alteradas y con slide de fugas.
          li 
            i.fas.fa-check
            | Ausencia de programas de mantenimiento preventivo.
      
      img.mb-4.mb-xl-0.col-xl-4.mx-auto.order-1.order-xl-2(src="@/assets/curso/temas/tema7/img-10.png" data-aos="fade-right")

    .row.justify-content-center.align-items-center.mb-5
      .col-md-10.col-lg-9.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/tema1/decorador-2.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4 Control ambiental del recurso hídrico   
                  p.text-small Para profundizar en el tema sobre el cuidado del recurso hídrico puede revisar el documento adjunto.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.minambiente.gov.co/wp-content/uploads/2021/10/Politica-nacional-Gestion-integral-de-recurso-Hidrico-web.pdf" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    p En la gestión avícola se debe tener en cuenta otro recurso, en este caso corresponde al aire en el plan de mitigación.

    Separador 
    #t_7_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 7.4 Recurso aire

    .row.justify-content-center.align-items-center
      .col-md-8.mb-4.mb-md-0(data-aos="fade-down-left")
        p La calidad del aire puede verse afectada por emisiones y olores ofensivos generados por la gallinaza o pollinaza, por los agentes en los productos utilizados para la limpieza y desinfección, por una mala disposición de residuos, y el aumento del CO y CO₂ producido por los vehículos de transporte ya sea de insumos y/o animales, huevos u otros producidos de las granjas avícolas.
        p La gallinaza y la pollinaza inician su proceso de descomposición inmediatamente después de ser excretada por las aves produciendo distintos gases, algunos de los cuales afectan el entorno y la salud de los trabajadores, causan molestias a los vecinos e impactos en la atmósfera, principalmente cuando los galpones están mal diseñados (pobre ventilación) y no se respeta la densidad de aves recomendada por los expertos o las operaciones de manejo no son las mejores. 
        p A continuación, se mencionan los gases de mayor impacto emitidos durante la descomposición de estos residuos son:
      .col-md-4.mb-4.mb-md-0(data-aos="fade-down")
        figure
          img(src='@/assets/curso/temas/tema7/img-11.png', alt='')

    LineaTiempoB.color-primario.mt-5.mb-5(:datos="datosLineaTiempoB")(data-aos="fade-left").BGIMG03

    p.mb-5 Como parte de las medidas de prevención, mitigación y/o control uso del aire, se deben tener en cuenta las siguientes pautas: 

    .row.mb-5.justify-content-center.align-items-center.mb-5
      .col-12.col-md-5.mb-5.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/temas/tema7/img-12.png', alt='')  
      .col-12.col-md-7.mb-lg-0(data-aos="fade-left")
        ul.lista-ul--color
          li 
            i.fas.fa-check
            | Mantenimiento preventivo de equipos (calderas, hornos).
          li 
            i.fas.fa-check
            | Monitoreo de la calidad de los combustibles (ACPM, carbón).
          li 
            i.fas.fa-check
            | Los equipos deben tener la capacidad necesaria y suficiente para satisfacer las demandas energéticas de la empresa; no contar con equipos sobredimensionados, con mayor capacidad de generación que la requerida por la planta.
          li 
            i.fas.fa-check
            | Se debe contar con equipos que cumplan con las especificaciones técnicas que garanticen el cumplimiento de la normativa vigente (Resolución 909 de 2008, MAVDT).
          li 
            i.fas.fa-check
            | Realizar análisis periódicos de la calidad de emisiones. 

    .row.justify-content-center.align-items-center.mb-5
      .col-md-10.col-lg-9.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/tema1/decorador-2.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4 Recurso aire  
                  p.text-small Para profundizar el conocimiento sobre el recurso aire puede revisar la “Guía ambiental para el subsector avícola'' de la Federación Nacional de Avicultores de Colombia - FENAVI.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://fenavi.org/wp-content/uploads/2018/05/GUIA_AMBIENTAL_SUBSECTOR_AVICOLA.pdf" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_1_1 Olores ofensivos

    .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema7/img-13.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 De acuerdo con la Resolución 1541 de 2013, un olor ofensivo se define como el olor generado por sustancias o actividades industriales, comerciales o de servicio que causa molestia, aunque no presente riesgos para la salud humana. Estos olores deben ser controlados mediante la implementación de un plan de contingencia diseñado para reducir su impacto, comúnmente conocido como Plan de Reducción de Olores (PRIO), según sus siglas.
          br
          br
          | Los olores ofensivos provenientes de instalaciones avícolas son producidos por una mezcla de gases y vapores, muchos de los cuales se generan por la descomposición anaerobia de la gallinaza o pollinaza, la mortalidad, alimentos y otras materias orgánicas.

    .col-xl-10.mx-auto.mb-5
      .titulo-sexto.color-primario(data-aos="fade-right")
        h5 Figura 5.
        span <em>Propagación de olores y sus mecanismos</em>
      img.d-md-block(src="@/assets/curso/temas/tema7/img-14.svg" data-aos="fade-left" alt="En la figura 5 se muestra la propagación de olores y sus mecanismos.")
      figcaption Nota: tomada del Manual de buenas prácticas disponibles para la mitigación de olores en la industria avícola, Federación Nacional de Avicultores de Colombia FENAVI - FONAV (2018)

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_1_1 Control de olores ofensivos

    .d-flex.flex-wrap.mb-5
      .col-xl-8.pe-xl-4.d-flex.flex-wrap.align-items-center.order-2.order-xl-1
        .tarjeta.color-acento-contenido.p-4.d-flex.flex-wrap(data-aos="fade-right" style="background-color:#ABFFFF")
          .col-md-11.ps-lg-4
            p.mb-0(style="color: #000") Los olores se generan inevitablemente en donde hay producciones pecuarias, pero la prevención y el manejo pueden hacerse teniendo en cuenta las acciones para el manejo de control de olores desde el lugar donde se originan, es decir desde la fuente, ya que estas son más efectivas y más fácil de implementar que las medidas orientadas al medio o al receptor, que requieren de mayor inversión y tiempo, y en la mayoría de casos su adopción es impráctica y poco efectiva. 
              br
              br
              | Desde este punto de vista las buenas prácticas en las granjas avícolas son la mejor manera de aplicar las medidas de prevención y control de la emisión de gases y malos olores generados por el proceso productivo.
      img.mb-4.mb-xl-0.col-xl-4.mx-auto.order-1.order-xl-2(src="@/assets/curso/temas/tema7/img-15.png" data-aos="fade-left" style="max-width: 400px")

    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2#t_1_1 Autodiagnóstico de emisión de olores ofensivos 

    p El autodiagnóstico se practica en lugares aledaños como casas vecinas o puntos ubicados alrededor de la producción, los cuales han sido escogidos previamente. La recomendación es que se realice con regularidad sobre todo cuando el viento se dirige en dirección a los puntos seleccionados, con el fin de que se obtenga una mejor concentración de olores ofensivos provenientes de la producción.  Esta actividad puede medir el impacto de actividades como la remoción de camas o el paleo de pilas de compost, las cuales pueden causar altos picos de emisión de olores.
    p.mb-5 Para guiar el autodiagnóstico el operario debe hacer las siguientes preguntas:

    .col-12.d-flex.flex-wrap.align-items-center.p-2.mb-5
      .col-12.col-md-3.col-lg-2
        img.mb-4.mb-md-5.mx-auto(src="@/assets/curso/temas/tema7/decorador-5.svg" data-aos="fade-right" style="max-width: 100px")
      ul.lista-ul--color(data-aos="fade-down")
        li 
          i.fas.fa-check
          | ¿En qué medida aumenta la emisión de olores cuando se realizan operaciones críticas como las ya mencionadas?
        li 
          i.fas.fa-check
          | ¿Aumenta la recepción de quejas en esas ocasiones?
        li 
          i.fas.fa-check
          | ¿Existen pilas de materia orgánica?
        li 
          i.fas.fa-check
          | ¿En qué condiciones está almacenada?
        li 
          i.fas.fa-check
          | ¿Está cubierta?
        li 
          i.fas.fa-check
          | ¿Dónde están ubicados los puntos de almacenamiento de materia orgánica con respecto a las casas vecinas? 

    p.mb-5 La siguiente escala es sugerida para el registro de la emisión de olores en el autodiagnóstico:

    .col-12.d-flex.flex-wrap.align-items-center.p-2.mb-5
      .col-12.col-md-3.col-lg-2
        img.mb-4.mb-md-5.mx-auto(src="@/assets/curso/temas/tema7/decorador-6.svg" data-aos="fade-right" style="max-width: 100px")
      ul.lista-ul--color(data-aos="fade-down")
        li 
          i.fas.fa-check
          | Olor indetectable.
        li 
          i.fas.fa-check
          | Olor tenue (apenas detectable, se requiere permanecer detenido en un sitio e inhalar en contra de la dirección del viento).
        li 
          i.fas.fa-check
          | Olor moderado (fácilmente detectable durante una caminata y respirando normalmente).
        li 
          i.fas.fa-check
          | Olor fuerte (fuerte pero tolerable).
        li 
          i.fas.fa-check
          | Olor muy fuerte (bastante ofensivo, puede causar náusea, especialmente si el receptor no está acostumbrado al olor).

    p.mb-5 La persona que realiza el diagnóstico debe tomarse al menos tres minutos en los puntos de monitoreo fijados previamente, y si el olor es detectado, se debe valorar su extensión de acuerdo con la siguiente escala:
    
    .col-12.d-flex.flex-wrap.align-items-center.p-2.mb-5
      .col-12.col-md-3.col-lg-2
        img.mb-4.mb-md-5.mx-auto(src="@/assets/curso/temas/tema7/decorador-7.svg" data-aos="fade-right" style="max-width: 100px")
      ul.lista-ul--color(data-aos="fade-down")
        li 
          i.fas.fa-check
          | Olor local y transitorio (sólo percibido dentro de los galpones o en el perímetro de la granja).
        li 
          i.fas.fa-check
          | Olor transitorio pero detectable por fuera del perímetro de la granja.
        li 
          i.fas.fa-check
          | Persistente, pero apenas localizado.
        li 
          i.fas.fa-check
          | Persistente y generalizado hasta 50 metros por fuera del perímetro de la granja.
        li 
          i.fas.fa-check
          | Persistente y extendido (más de 50 metros por fuera del perímetro de la granja).

    p.mb-5 Los resultados de las apreciaciones de intensidad y extensión de la emisión de olores deben ser registrados de la siguiente forma:

    .row.justify-content-center.align-items-center.mb-5
      .col-md-10.col-lg-9.mb-4.mb-md-0(data-aos="fade-left")
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/temas/tema1/decorador-2.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4 Autodiagnóstico para el control de olores ofensivos
                  p.text-small Para conocer más sobre el control de olores ofensivos en la industria avícola se puede consultar el “Manual de buenas prácticas disponibles para la mitigación de olores en la industria avícola” 
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://fenavi.org/wp-content/uploads/2018/05/Cartilla_Digital_PRIO_FINAL.pdf" target="_blank")
                    span Descargar
                    i.fas.fa-file-download



</template>

<script>
export default {
  name: 'Tema7',
  data: () => ({
    datosLineaTiempoB: [
      {
        titulo: '1. Ácidos orgánicos volátiles',
        texto:
          'Estos compuestos son generados durante la hidrólisis de los ácidos grasos presentes en el estiércol; se destacan los ácidos acéticos, propiónico, butírico, valérico y capróico, que se caracterizan por su volatilidad y olor penetrante. Por su carácter ácido, en condiciones ambientales adversas (p.ej. pobre ventilación versus exposición prolongada) causan irritaciones en las mucosas del sistema respiratorio de aves y humanos.',
        icono: require('@/assets/curso/temas/tema7/gallina-1.png'),
      },
      {
        titulo: '2. Amoniaco',
        texto:
          'Se forma por la descomposición de la urea presente en la gallinaza y la pollinaza. Este es un gas alcalino irritante y de olor penetrante, que cuando se concentra en un espacio cerrado no sólo causa irritación del sistema respiratorio, sino que también afecta los ojos.',
        icono: require('@/assets/curso/temas/tema7/amoniaco-2.png'),
      },
      {
        titulo: '3. Metano',
        texto:
          'Es un gas combustible producido en condiciones anaeróbicas, es decir, cuando la gallinaza y la pollinaza superan el 80 % de humedad. El metano (CH₄), tiene la capacidad de absorber radiación infrarroja propiciando el calentamiento gradual de la atmósfera, lo que se conoce como efecto invernadero. El índice de absorción de radiación infrarroja del metano es de 58 en una escala en la cual el valor de referencia de uno, corresponde al dióxido de carbono (CO₂).',
        icono: require('@/assets/curso/temas/tema7/metano-3.png'),
      },
      {
        titulo: '4. Dióxido de carbono',
        texto:
          'Es producto tanto de la descomposición aeróbica como anaeróbica de los estiércoles. Es un gas inerte y tiene efectos tóxicos en elevadas concentraciones; es el principal agente causante del efecto invernadero por su capacidad de absorber radiación infrarroja y por ser una de las mayores emisiones atmosféricas antropogénicas, debido a que también se genera como resultado de la combustión.',
        icono: require('@/assets/curso/temas/tema7/carbono-4.png'),
      },
      {
        titulo: '5. Gas sulfhídrico, H₂S',
        texto:
          'Se produce por la degradación biológica en condiciones anaerobias de los compuestos azufrados. El gas sulfhídrico o sulfuro de hidrógeno tiene el olor característico del «huevo podrido» perceptible a concentraciones muy bajas (2 ppm). Es el principal agente aromático de las emisiones provenientes de la descomposición del estiércol y es un gas altamente corrosivo, que afecta principalmente los metales ferrosos.',
        icono: require('@/assets/curso/temas/tema7/gas-5.png'),
      },
      {
        titulo: '6. Partículas respirables',
        texto:
          'La caspa que emiten las aves y el polvo proveniente de las camas y del alimento concentrado, se suspenden fácilmente en el aire dentro de los galpones donde los trabajadores se exponen a inhalar estas partículas que, con el tiempo, pueden causar una afección crónica denominada asma ocupacional, principalmente en aquellos mal diseñados o en explotaciones con densidades inadecuadas de aves.',
        icono: require('@/assets/curso/temas/tema7/particulas-6.png'),
      },
    ],
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
