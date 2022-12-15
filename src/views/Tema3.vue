<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Bases conceptuales de medio ambiente, impacto ambiental y línea base ambiental 
    p Estimado aprendiz, a lo largo de esta temática usted revisara los siguientes conceptos:
    separador
    #t_3_1.titulo-segundo.color-acento-contenido
      h2 3.1 Bases conceptuales medio ambiente
    .row.mb-4
      .col-lg-3
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Individuo y especie
    h4 Individuo
    .row.mt-4
      .col-lg-8
        p Todo ser vivo, independientemente de su complejidad biológica, es un individuo, capaz de realizar todas las funciones vitales: nutrición, relación y reproducción. Se refiere al individuo de una especie. Ejemplo el perro pepe es un individuo único en el universo y se llama pepe.
        .row
          .col-lg-9.mt-4
            .tarjeta.color-primario.p-3.mb-5
              .row.justify-content-around.align-items-center
                .col-3.col-sm-2.col-lg-1
                  img(src="@/assets/curso/t3/www.svg")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0
                      p.text-small ABC (2013, octubre 7) Individuo, población, comunidad
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-file-download      
        h4 Especie
        p.mb-0 Forma en la que se agrupan los seres vivos. Por ejemplo, los cernícalos forman parte de la misma especie, al igual que los gatos, los perros, los leones, las tabaibas o los laureles. 
        p ABC (2013, octubre 7) Individuo, población, comunidad.
      .col-lg-4
        img(src="@/assets/curso/t3/1.svg", alt="Texto que describa la imagen")
    .row.mb-4.mt-4
      .col-lg-2
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Población
    .row
      .col-lg-8
        p.mb-0 Miembros de la misma especie que habitan en un ecosistema. Por ejemplo, la población de cernícalos de la isla de gran canaria son todos los cernícalos que en la isla habitan. 
        p ABC (2013, octubre 7) Individuo, población, comunidad.
        .row
          .col-lg-9.mt-4
            .tarjeta.color-primario.p-3.mb-5
              .row.justify-content-around.align-items-center
                .col-3.col-sm-2.col-lg-1
                  img(src="@/assets/curso/t3/www.svg")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0
                      p.text-small ABC (2013, octubre 7) Individuo, población, comunidad
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-file-download      
      .col-lg-4
        img(src="@/assets/curso/t3/2.svg", alt="Texto que describa la imagen")
    .row.mb-4.mt-4
      .col-lg-2
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Comunidad
    .row
      .col-lg-8
        p.mb-0 Es el conjunto de poblaciones de un ecosistema. Por ejemplo, son todos los animales que habitan en un bosque.
        p ABC (2013, octubre 7) Individuo, población, comunidad.
        .row
          .col-lg-9.mt-4
            .tarjeta.color-primario.p-3.mb-5
              .row.justify-content-around.align-items-center
                .col-3.col-sm-2.col-lg-1
                  img(src="@/assets/curso/t3/www.svg")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0
                      p.text-small ABC (2013, octubre 7) Individuo, población, comunidad
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-file-download            
      .col-lg-4
        img(src="@/assets/curso/t3/3.svg", alt="Texto que describa la imagen")
    .row.mb-4.mt-4
      .col-lg-2
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Ecosistema
    p Un Ecosistema es un conjunto formado por un espacio determinado y todos los seres vivos que lo habitan. Por ello podemos decir que están formados por el medio físico y los seres vivos que en él se encuentran. Los ecosistemas se pueden clasificar en terrestres (bosques, praderas o desiertos) o acuáticos (de agua dulce o de agua salada). Los ecosistemas pueden ser de diversos tamaños, desde una charca a todo un océano, de hecho, podemos considerar a La Tierra y todos los seres vivos que en ella habitan como un gran ecosistema. A este gran ecosistema se le llama la BIOSFERA (BIO = VIDA + ESFERA).
    .row.justify-content-center
      .col-lg-6
        .row
          .col-lg-12.mt-4
            .tarjeta.color-primario.p-3.mb-5
              .row.justify-content-around.align-items-center
                .col-3.col-sm-2.col-lg-1
                  img(src="@/assets/curso/t3/www.svg")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0
                      p.text-small CAR (s,f) Glosario de términos ambientales
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-file-download      
    .row.justify-content-center.mt-4
      .col-lg-10
        img(src="@/assets/curso/t3/4.svg", alt="Texto que describa la imagen")
    .row.mb-4.mt-4
      .col-lg-3
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Tipos de ecosistema
    p En el mundo existen diversos tipos de ecosistema se le invita a observa la riqueza de ecosistemas que tiene nuestro país Colombia, recuerde que tener diversos ecosistemas es tener varias comunidades, poblaciones de diferentes especies que se adaptan a ese entorno por eso Colombia es rica en biodiversidad.        
    .row.justify-content-center.mt-4
      .col-lg-5
        img(src="@/assets/curso/t3/5.svg", alt="Texto que describa la imagen")

      .col-lg-5
        img(src="@/assets/curso/t3/6.svg", alt="Texto que describa la imagen")
    .row.mb-4.mt-4
      .col-lg-2
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Medioambiente
    p En el mundo existen diversos tipos de ecosistema se le invita a observa la riqueza de ecosistemas que tiene nuestro país Colombia, recuerde que tener diversos ecosistemas es tener varias comunidades, poblaciones de diferentes especies que se adaptan a ese entorno por eso Colombia es rica en biodiversidad.
    p.text-center Descubra las letras que están en la imagen, haga clic en cada uno y visualice su información.
    .row.bg1.justify-content-center
      .col-lg-6
        ImagenInfografica.color-acento-botones
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/t3/7.svg', alt='Texto que describa la imagen')

          .tarjeta.color-acento-botones.p-3(x="50%" y="10%" numero="A")
            p Por tanto, el medio ambiente seria la generalidad de incluir todos los ecosistemas incluyendo el ecosistema urbano creado por los seres humanos, por eso la definición social de que medio ambiente es todo lo que nos rodea.
            p En el diagnóstico ambiental que se realice en la organización se incluye los recursos naturales como son flora, fauna, agua, suelo, aire, pero también el social (incluyendo las actividades humanas) como parte de un todo.
          .tarjeta.color-acento-botones.p-3(x="15%" y="50%" numero="B")
            p La definición especifica es la Conferencia de las Naciones Unidas sobre Medio Ambiente en Estocolmo (1972) lo define como: “Medio ambiente es el conjunto de componentes físicos, químicos, biológicos y sociales capaces de causar efectos directos o indirectos, en un plazo corto o largo, sobre los seres vivos y las actividades humanas”, citado en el libro “Agenda 21” de Foy (1998).
          .tarjeta.color-acento-botones.p-3(x="90%" y="50%" numero="C")
            p La definición según la ISO 14001:2015 Medio ambiente: es todo aquello que rodea al ser humano y que comprende elementos naturales, tanto físicos como biológicos, elementos artificiales y elementos sociales y las interacciones de éstos entre sí.
    .row.mb-4.mt-4
      .col-lg-2
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Cambio climático
    .row
      .col-lg-7
        p La Convención Marco de las Naciones Unidas sobre el Cambio Climático (CMNUCC), en su artículo 1, define el cambio climático como “cambio de clima atribuido directa o indirectamente a la actividad humana que altera la composición de la atmósfera global y que se suma a la variabilidad natural del clima observada durante períodos de tiempo comparables”. IPCC (2018) Glosario p. 188.
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t3/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 IPCC, 2013: Glosario [Planton, S. (ed.)]. En:
                  p.text-small Cambio Climático 2013. Bases físicas. Contribución del Grupo de trabajo I al Quinto Informe de Evaluación del Grupo Intergubernamental de Expertos sobre el Cambio Climático [Stocker, T.F., D. Qin, G.-K. Plattner, M. Tignor, S.K. Allen, J. Boschung, A. Nauels, Y. Xia, V. Bex y P.M. Midgley (eds.)]. Cambridge University Press, Cambridge, Reino Unido y Nueva York, NY, Estados Unidos de América. 
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download      
      .col-lg-5
        img(src="@/assets/curso/t3/8.svg", alt="Texto que describa la imagen")
    .row.mb-4.mt-4
      .col-lg-2
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Efecto ivernadero
    .row
      .col-lg-7
        p El IPCC Panel Intergubernamental sobre Cambio Climático establece que el efecto invernadero, es el  efecto radiactivo infrarrojo de todos los componentes de la atmósfera que absorben en el infrarrojo, por lo tanto los gases de efecto invernadero y las nubes y, en menor medida, los aerosoles absorben la radiación terrestre emitida por la superficie de la Tierra, esta modificación de la concentración de los gases de efecto invernadero debida a emisiones antropógenas contribuye a un aumento de la temperatura en la superficie o índice de calentamiento.
        p IPCC (2018) Glosario p. 190.
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t3/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 IPCC, 2013: Glosario [Planton, S. (ed.)]. En:
                  p.text-small Cambio Climático 2013. Bases físicas. Contribución del Grupo de trabajo I al Quinto Informe de Evaluación del Grupo Intergubernamental de Expertos sobre el Cambio Climático [Stocker, T.F., D. Qin, G.-K. Plattner, M. Tignor, S.K. Allen, J. Boschung, A. Nauels, Y. Xia, V. Bex y P.M. Midgley (eds.)]. Cambridge University Press, Cambridge, Reino Unido y Nueva York, NY, Estados Unidos de América.
                
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download     
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download    
      .col-lg-5
        img(src="@/assets/curso/t3/9.svg", alt="Texto que describa la imagen")
    .row.mt-4.bg2.align-items-center
      .row
        .col-lg-2
          .row.estilo1.p-2
            h3.text-white.text-center.mb-0 Capa de ozono
      .row.align-items-center
        .col-lg-7
          p El IPCC (2013) Panel Intergubernamental sobre Cambio Climático establece que la capa de ozono define que en la estratosfera contiene una capa en que la concentración de ozono es máxima, denominada capa de ozono. Esta capa abarca aproximadamente desde los 12 km hasta los 40 km por encima de la superficie terrestre. La concentración de ozono alcanza un valor máximo entre los 20 km y los 25 km aproximadamente. Esta capa ha sido mermada por efecto de las emisiones humanas de compuestos de cloro y de bromo.  IPCC (2018) Glosario p. 188.
        .col-lg-5
          img(src="@/assets/curso/t3/10.svg", alt="Texto que describa la imagen")
    .tarjeta.color-primario.p-3.mb-5.mt-4
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/curso/t3/pdf.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h3.mb-1 IPCC, 2013: Glosario [Planton, S. (ed.)]. En:
              p.text-small Cambio Climático 2013. Bases físicas. Contribución del Grupo de trabajo I al Quinto Informe de Evaluación del Grupo Intergubernamental de Expertos sobre el Cambio Climático [Stocker, T.F., D. Qin, G.-K. Plattner, M. Tignor, S.K. Allen, J. Boschung, A. Nauels, Y. Xia, V. Bex y P.M. Midgley (eds.)]. Cambridge University Press, Cambridge, Reino Unido y Nueva York, NY, Estados Unidos de América.
            .col-sm-auto
              a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download     
            .col-sm-auto
              a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download     
    .row.bg3.justify-content-center
      p.text-center Continúe viendo información, haga clic en cada título de la infografía y visualiza lo que trata.
      .col-lg-6
        ImagenInfografica.color-acento-botones
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/t3/11.svg', alt='Texto que describa la imagen')

          .tarjeta.color-acento-botones.p-3(x="30%" y="40%" numero="")
            h5 Calentamiento Global

            p La PNCC (2017) que es sus siglas      traduce: (política nacional de cambio climático) establece que el calentamiento global es causado por las emisiones de gases de efecto invernadero generadas por distintas actividades humanas y coincide en afirmar que dicho cambio ha ocasionado impactos en sistemas humanos y naturales en todo el mundo. De continuar con la tendencia de emisiones, la temperatura promedio global aumentará en más de 4 °C y consecuentemente se incrementará la probabilidad de impactos climáticos severos e irreversibles como la pérdida de ecosistemas, inseguridad alimentaria, inundaciones, entre      otros. MINAMBIENTE (2017) Política Nacional de Cambio Climático p.31

          .tarjeta.color-acento-botones.p-3(x="10%" y="60%" numero="")
            h5 Evaluación de impacto ambiental
            p La CAR (Corporación Autónoma Regional) define que la evaluación de impacto ambiental es el resultado de medir y ponderar los efectos de las actividades del desarrollo humano o la carencia de acciones sobre distintos componentes del medio ambiente durante una etapa de planeación. 
          .tarjeta.color-acento-botones.p-3(x="90%" y="60%" numero="")
            h5 Impacto ambiental

            p La CAR (corporación Autónoma Regional)      establece que el impacto ambiental es cualquier alteración en el medio físico, químico, biológico, cultural y socioeconómico que pueda ser atribuido a actividades humanas relacionadas con las necesidades del proyecto.
          .tarjeta.color-acento-botones.p-3(x="70%" y="30%" numero="")
            h5 Contaminación
            p Se entiende por contaminación la alteración del ambiente con sustancias o formas de energía puestas en él, por actividad humana o de la naturaleza, en cantidades, concentraciones o niveles capaces de interferir el bienestar y la salud de las personas, atentar contra la flora y la fauna, degradar la calidad del ambiente de los recursos de la nación o de los particulares.
          .tarjeta.color-acento-botones.p-3(x="50%" y="80%" numero="")
            h5 Contaminante

            p Se entiende por contaminante cualquier elemento, combinación de elementos, o forma de energía que actual o potencialmente pueda producir alteración ambiental de las precedentemente descritas. La contaminación puede ser física, química o biológica.
    h4.text-center Conclusión
    .row.mb-5
      .col-sm.mb-5.mb-sm-0
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span a
            | Los seres vivos presentan varios niveles de organización que van desde el nivel atómico o molecular, la célula, los tejidos, los órganos, los organismos (seres vivos como tal representando un individuo de una especie), población (varios individuos de la misma especie), comunidad (varias especies que conviven juntas y que tienen interacciones como cadena alimenticia, mutualismo, comensalismo, simbiosis, etc., ecosistema ( varias comunidades en un mismo ambiente especifico) hasta Medio Ambiente todo lo que nos rodea.

          li 
            .lista-ol--cuadro__vineta
              span b
            | Estos conceptos son relevantes para entender la diferencia en cuanto a problemas legales ambientales cuando se dice que una empresa acaba con un ecosistema es una opinión que puede tener demandas millonarias porque esto redunda muchas especies y un medio específico con característica.

          li 
            .lista-ol--cuadro__vineta
              span c
            | Muchas veces estas empresas disminuyen la connotación al haber afectado una población o un individuo para que la multa      disminuya, pero esto no quiere decir que sea menos importante, puede ser una especie en vía de extinción, importante para mantener el eslabón de la cadena      alimenticia, una especie con unas funciones eco sistemáticas esenciales para este, si es cría o hembra.  

          li 
            .lista-ol--cuadro__vineta
              span d
            | Todas estas variables      que dependen de los casos pueden ser de multas millonarias, pero muchas veces las empresas tienen el dinero para pagar las multas, por tanto, también existen sanciones de sellamiento y cerramiento.

          li 
            .lista-ol--cuadro__vineta
              span e
            | Reconocer los hábitats de las especies en el área de influencia del proyecto o de una organización y reconocer las actividades de la organización si afectan ese hábitat de manera directa a la especie o de manera indirecta contaminando o afectando el agua, el suelo, el aire, esto nos sirve para identificar medidas de prevención y mitigación ambiental.
          li 
            .lista-ol--cuadro__vineta
              span f
            | Por eso algunas empresas prefieren que los ambientes ya estén intervenidos por el hombre para no afectar el medio y es ahí donde vemos que personas inescrupulosas realizan casos ilegales como rellenar de basura y escombros los humedales para que estos se extingan y cuando ya no se pueda hacer nada por él sea más fácil obtener la licencia de construcción en esta zona a futuro.
    .row.justify-content-center.mt-4
      .col-lg-10
        img(src="@/assets/curso/t3/12.svg", alt="Texto que describa la imagen")
    separador
    #t_3_2.titulo-segundo.color-acento-contenido
      h2 3.2 Componentes Ambientales
    p Aspectos ambientales que constituyen un medio (abiótico o inerte, biótico o socioeconómico) como, por ejemplo, componente atmosférico, hidrológico, faunístico, demográfico, entre otros.
    p En términos generales, en el marco del proceso de licenciamiento ambiental los aspectos a evaluar para la determinación del área de influencia se deben plantear considerando una organización jerárquica de medio y componente, en la cual, los medios se entienden como la división general del ambiente y máxima categoría de abordaje, y los componentes corresponden a los elementos ambientales que constituyen un medio, como se presenta a continuación:
    .titulo-sexto.color-acento-contenido
      h5 Tabla 1.
      span Componentes ambientales
    .tabla-b.color-acento-contenido.mb-5
      .tabla-b__header
        h4.mb-0 Estudio de línea base
      table
        caption Fuente: PROGuía No. 1 Elaboración de estudios de impacto ambiental 2004 - DEVIDA. Enlace: https://drive.google.com/drive/u/0/folders/1R5yyGtgp6ogsVCAT2n6qq5OTTKED9pwu
        tr
          th 1. Descripción del ambiente físico
          td • Clima: temperatura, altitud, precipitación pluvial, humedad relativa.<br>• Recurso hídrico: cursos de agua, quebradas, lagos, sistemas marinos.<br>• Recurso suelo: Tipología, edafología, morfología, fisiografía, uso actual de la tierra, capacidad de uso mayor, sismología.<br>• Recurso aire: Calidad del aire, nivel de ruidos, olores
        tr
          th 2. Descripción del ambiente biótico
          td • Zonas de vida y biotipos: bosques, humedales, pantanos, boquerones, etc.<br>• Flora silvestre: especies principales.<br>• Fauna silvestre: especies principales.<br>• Población humana: salud, vivienda, urbanismo, saneamiento.
        tr
          th 3. Descripción del ambiente socioeconómico
          td • Demografía: distribución poblacional, tipo de asentamientos.<br>• Ocupación y utilización del espacio territorial: acondicionamiento territorial<br>• Actividades económicas principales: agricultura, turismo, minería, hidrocarburos, industria, etc.
        tr
          th 4. Recursos culturales
          td Zonas de interés histórico, turístico, arqueológico.
    .row.mt-5
      .col-lg-2
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 El medio abiótico
    p.mt-4 Contiene los componentes geológico, geomorfológico, paisaje, suelo y uso del suelo, hidrológico, hidrogeológico, oceanográfico, geotécnico y atmosférico, entre otros.
    .row.mt-5
      .col-lg-2
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 El medio biótico
    p.mt-4 Comprende los componentes flora, fauna e hidrobiota. 
    .row.mt-5
      .col-lg-3
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 El medio socioeconómico
    p.mt-4 Consta de los componentes demográfico, espacial, económico, cultural, arqueológico y político-organizativo.
    .row.justify-content-center
      .col-lg-6
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t3/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.text-small Jorge Arboleda (2008) Manual EIA. Pág. 21
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download     
    .row.mt-5
      .col-lg-3
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Área de influencia
    p.mt-4 Para definir el área de influencia, es necesario estimar la localización, tipo e intensidad de uso de los recursos durante las distintas fases del desarrollo del proyecto, obra o      actividad, así como considerar los impactos generados sobre estos y su variación en tiempo y espacio.
    .row.justify-content-center
      .col-lg-6
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t3/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.text-small Jorge Arboleda (2008) Manual EIA. Pág. 21
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download    
    h4.mt-4 • Área de influencia directa (AID)
    p El área de influencia directa es aquella donde se presentan los impactos generados en las fases de construcción y/o operación de un proyecto, obra o actividad; está relacionada con el sitio donde se ubica la organización y su infraestructura. 
    p De acuerdo con el impacto generado el área puede o no cambiar y de acuerdo a esto se deben delimitar las áreas de influencia sobre todos los componentes. La caracterización del AID debe ofrecer una visión detallada de los componentes.   
    .row.justify-content-center
      .col-lg-8
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t3/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 CESEL INGENIEROS (2015)
                  p.text-small Estudio de impacto ambiental del proyecto “Central Hidroeléctrica Chilia” Ancash-Huáuco. Capítulo 4 Descripción del área de influencia directa e indirecta pág. 1
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download    
    h4.mt-4 • Área de influencia indirecta (AII)
    p El área donde los impactos se propagan hacia la zona externa al área de influencia directa y se extiende tanto como el efecto del impacto lo permita.
    .row.justify-content-center
      .col-lg-8
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t3/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 CESEL INGENIEROS (2015)
                  p.text-small Estudio de impacto ambiental del proyecto “Central Hidroeléctrica Chilia” Ancash-Huáuco. Capítulo 4 Descripción del área de influencia directa e indirecta pág. 2
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download       
    .row.mt-5
      .col-lg-8
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Metodología para la recolección de información de los componentes ambientales  
    .row.mb-5.mt-4
      .col-sm.mb-5.mb-sm-0
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span a
            | Consultar información secundaria del área de estudio  como cartográfica referente a cada uno de los componentes (p.ej. Googlemaps, Guía de Zonificación y Codificación de Cuencas Hidrográficas, publicada por el Instituto de Hidrología, Meteorología y Estudios Ambientales - IDEAM y el Ministerio de Ambiente y Desarrollo Sostenible – MADS, planchas del Servicio Geológico Colombiano, fotografías satelitales e imágenes de sensores remotos, bases cartográficas del IGAC, información cartográfica oficial disponible respecto a la división político-administrativa del área de estudio, entre otros), así como información de fuentes oficiales de índole local, regional y nacional (POMCAS, Instrumentos de ordenamiento territorial, ERA, ENA, entre otros), teniendo en cuenta la localización del proyecto, obra o actividad.

          li 
            .lista-ol--cuadro__vineta
              span b
            | Realizar reconocimiento del área, con el fin de corroborar la información secundaria consultada y la establecida en las imágenes satelitales, haciendo uso de recorridos definidos y estableciendo y/o ratificando puntos de interés para el levantamiento de información y/o muestreos.
          li 
            .lista-ol--cuadro__vineta
              span c
            | A partir de esta información identificar aspectos relevantes y establecer puntos de interés por su vulnerabilidad o conservación ambiental y social de los medios físicos, como bióticos y socioeconómicos.
          li 
            .lista-ol--cuadro__vineta
              span d
            | Definir y/o identificar las actividades propuestas para las diferentes fases, de acuerdo con las necesidades del proyecto, obra o actividad. 
          li 
            .lista-ol--cuadro__vineta
              span e
            | Identificar y definir las unidades mínimas de análisis para cada uno de los componentes (p.ej. hídrico, geológico, geomorfológico, flora, fauna, demográfico, espacial, cultural, entre otros), que se presenten como relevantes.
          li 
            .lista-ol--cuadro__vineta
              span e
            | Teniendo en cuenta lo anterior, obtener, definir y/o delimitar un área de influencia directa e indirecta.  trazar un polígono con base en la información estableciendo el área donde se manifestarían los impactos ambientales significativos para cada uno de los componentes de los medios abiótico, biótico y socioeconómico, utilizando criterios y variables relacionados con la presencia de elementos o condiciones que se evidencian como factores que inciden en la trascendencia de los posibles impactos, como: cambios de coberturas de la tierra, geo formas, puntos de convergencia de dos cuerpos de agua, cambios de pendiente, posibles puntos de captación y vertimiento, divisiones territoriales, entre otros.
    .row.justify-content-center
      .col-lg-8
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t3/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.text-small En caso de mayor detalle de la información requerida para realizar el inventario ambiental o línea base ambiental de los componentes ambientales ver la      guía (Ambientales, 2018).
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download       
    .row.justify-content-center.mt-4
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t3/www.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.text-small En caso de construir un inventario ambiental o línea base ambiental de los componentes ambientales para un estudio de impacto ambiental para el otorgamiento de una licencia ambiental debe acatarse adicionalmente los términos de referencia que dicta el ANLA Autoridad Nacional de Licencias Ambientales si aplica para el tipo de proyecto en el cual le mencionan que tener en cuenta los requisitos específicos que solicita      la autoridad ambiental. Ver página web 
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Enlace web
                    i.fas.fa-file-download       
    .row.mt-5
      .col-lg-4
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Tipos de Componentes Ambientales
    p.mt-3 Para definir el área de influencia, es necesario estimar la localización, tipo e intensidad de uso de los recursos durante las distintas fases del desarrollo del proyecto, obra o      actividad, así como considerar los impactos generados sobre estos y su variación en tiempo y espacio.
    img.mt-4(src="@/assets/curso/t3/13.svg")
    p.mt-4.mb-0 • El medio abiótico contiene los componentes geológico, geomorfológico, paisaje, suelo y uso del suelo, hidrológico, hidrogeológico, oceanográfico, geotécnico y atmosférico, entre otros. 
    p.mt-4.mb-0 • El medio biótico comprende los componentes flora, fauna e hidrobiota. 
    p.mt-4 • El medio socioeconómico consta de los componentes demográfico, espacial, económico, cultural, arqueológico y político-organizativo.
    p A continuación se describe cada componente:
    h4 • Ambiente Físico
    p Incluye los componentes abióticos del ecosistema
    img(src="@/assets/curso/t3/14.svg")
    .row
      .col-lg-6
        .row.p-3.colort1
          h5.mb-0 Recursos Hídricos:
          p Se incluyen todos los aspectos de los recursos hídricos superficiales y subterráneos, empezando por sus características físicas básicas (redes de drenaje, canales y zonas inundables, riberas y batimetría de lagos y estuarios, la capa freática y sus propiedades, el sistema de flujo de agua subterránea, la      cantidad (caudales) y calidad (cuando existan datos). Al igual que los recursos terrestres, la descripción incluye procesos y otras características dinámicas del medio ambiente, (por      ejemplo, diversidad biológica en lagos, lagunas y ríos, interacciones de las cadenas tróficas) y el manejo del agua (abastecimiento, uso, derechos de uso, estándares de calidad, regulaciones, planes para administrar zonas costeras, etc.)
      .col-lg-6
        .row.p-3.colort2
          h5.mb-0 Recursos del aire:
          p.mb-5 Incluye una descripción del clima y la meteorología (balance del agua, estaciones, calidad del aire), así como los temas referidos al ruido (niveles de ruido ambiental, la existencia de fuentes de ruido, sensibilidad de los receptores, las reglamentaciones ambientales), olores, calor y luz, que se incluyen en la categoría      de “aire”,      porque sus efectos son generalmente transmitidos a través de la atmósfera.
          .row.mb-5
          .row.mb-3
    AcordionA.mb-5.mt-4(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row.justify-content-center(titulo="Ambiente Biótico")
        .col-md-5.mb-4.mb-md-0
          p Referido fundamentalmente los ecosistemas existentes y la flora y fauna silvestre que habita en ellos.
          p Identifica las especies de flora y fauna silvestre características de la zona, los diferentes ecosistemas y zonas de vida, enfatizando la manera en que estos funcionan para garantizar la productividad biológica y la diversidad (por ejemplo, cómo la vegetación permite sostener la pesca y la vida silvestre,      cómo los hábitat de la vida silvestre soportan el ciclo de vida permitiendo la reproducción, migración, alimentación y protección).
          p Describe también áreas únicas, zonas en transición (bordes), otros recursos de especial importancia, y el uso de los recursos biológicos para la agricultura, silvicultura, pesca, etc.

        .col-md-6
          figure
            img(src='@/assets/curso/t3/15.png', alt='Texto que describa la imagen')

      .row.justify-content-center(titulo="Ambiente Socioeconómico")
        .col-md-5.mb-4.mb-md-0
          p Referido a las actividades humanas que se desarrollan dentro del ámbito del proyecto, entre estas las actividades sociales, económicas y culturales.

          p Esta categoría incluye la población humana (tamaño, distribución, etnia y otras características); actividades económicas (empleo, inversión, ingreso promedio, impuestos, etc.) en el área del proyecto. Usualmente, se incluye aquí una descripción de la infraestructura socioeconómica, como los servicios e instalaciones públicas y privadas, incluyendo el transporte, las viviendas, escuelas, parques, protección policial y contra incendio, servicios de salud, abastecimiento de agua y desagüe, manejo del agua de lluvia y desechos sólidos.

          p La discusión sobre la infraestructura puede extenderse a temas como el tráfico (donde el proyecto podría tener impacto en el corto o largo plazo sobre las vías de acceso o los niveles de tráfico), los recursos energéticos (por      ejemplo, el uso y conservación de la energía en un proyecto) y los materiales peligrosos.
        .col-md-6
          figure
            img(src='@/assets/curso/t3/16.png', alt='Texto que describa la imagen')
    h4.mt-4 Recursos Culturales y Estéticos
    .row.justify-content-center
      .col-lg-10
        img(src='@/assets/curso/t3/17.svg', alt='Texto que describa la imagen')
    .row.justify-content-center.mt-4
      .col-lg-12
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t3/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 ¡Estimado Aprendiz! Para profundizar en el tema lo invitamos a consultar en MATERIAL DE APOYO:

                  p.text-small 1. Guía para la definición, identificación y delimitación del área de influencia. ANLA Autoridad Nacional de licencias Ambientales.
                  p.text-small 2. Manual de evaluación de Impacto ambiental de proyectos, obras o actividades de Arboleda.
                  p.text-small 3. Plantaciones La Isla Flores de exportación. (2018) Estudio de impacto ambiental ex post y plan de manejo finca florícola la isla. Línea Base.
                  p.text-small 4. Probides (2001) Herramientas para la gestión ambiental.           
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Enlace web
                    i.fas.fa-file-download 
                  .row   
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Enlace web
                        i.fas.fa-file-download     
                  .row   
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Enlace web
                        i.fas.fa-file-download     
                  .row   
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Enlace web
                        i.fas.fa-file-download     
    .row.mt-5.bg4
      h4.text-center Conclusión
      .col-lg-4
        .row.mt-5
        .row.mt-5

        p.mt-5.mb-5 Es importante diagnosticar los componentes ambientales que están en el área de influencia del proyecto, obra o actividad para identificar los posibles impactos ambientales o mitigar los impactos que puede ocasionar por las labores humanas al entorno.
      .col-lg-4
      .col-lg-4
        .row.mt-5
        .row.mt-5

        p.mt-5.mb-5 La caracterización de los sistemas socio ecológicos, es una actividad que le permite al equipo de trabajo que está realizando el diagnóstico ambiental, conocer en detalle las características generales y particulares de la acción propuesta, desde la perspectiva de la especialidad o disciplina de cada una de las personas participantes.
        .row.mb-5
        .row.mb-4
    p.mt-4 Una salida de campo para visitar un sistema socio ecológico nos puede servir para identificar y describir dicho entorno.
    separador
    #t_3_3.titulo-segundo.color-acento-contenido
      h2 3.3 Bases conceptuales IMPACTO AMBIENTAL 
    .row.justify-content-center
      .col-lg-10
        .row.align-items-center
          .col-lg-9
            .row.p-3.colortt
              h5.mb-0 Aspecto ambiental:
              p Elemento de las actividades, productos o servicios de una organización que interactúa o puede interactuar con el medio ambiente.
              .tarjeta.color-primario.p-3.mb-5.mt-4
                .row.justify-content-around.align-items-center
                  .col-3.col-sm-2.col-lg-1
                    img(src="@/assets/curso/t3/pdf.svg")
                  .col
                    .row.justify-content-between.align-items-center
                      .col.mb-3.mb-sm-0

                        p.text-small ICONTEC (2015) NTC ISO 14001 Sistemas de Gestión Ambiental. Requisitos con orientación para su uso p 3.          
                      .col-sm-auto
                        a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                          span Descargar
                          i.fas.fa-file-download 
          .col-lg-3
            img(src='@/assets/curso/t3/m.svg', alt='Texto que describa la imagen')
        .row.mt-4.align-items-center
          .col-lg-3
            img(src='@/assets/curso/t3/h.svg', alt='Texto que describa la imagen')
          .col-lg-9
            .row.p-3.colortt1
              h5.mb-0 Tipos de aspecto ambiental:

              p Los aspectos ambientales son considerados positivos si ayudan al medio ambiente o negativos si desfavorecen al medio ambiente.
    .row.justify-content-center
      .col-lg-8        
        .row.mt-4.align-items-center

          .col-lg-9
            .row.p-3.colortt
              h5.mb-0 Ejemplos:
              p.mb-0 • Generación de residuos 
              p.mb-0 • Consumo de agua. 
              p.mb-0 • Consumo de materiales. 
              p.mb-0 • Consumo de agua. 
              p.mb-0 • Vertimientos. 
              p.mb-0 • Generación de ruidos. 
              p.mb-0 • Generación de residuos de aparatos eléctricos y electrónicos. 
          .col-lg-3
            img(src='@/assets/curso/t3/m.svg', alt='Texto que describa la imagen')
        .row.mt-4.align-items-center
          .col-lg-3
            img(src='@/assets/curso/t3/h.svg', alt='Texto que describa la imagen')
          .col-lg-9
            .row.p-3.colortt1
              p.mb-0 Emisiones atmosféricas por fuentes fijas y móviles. 

              p.mb-0  Generación de escombros y malos olores. 

              p.mb-0  Publicidad exterior visual. 

              p.mb-0  Educación ambiental. (+)

              p.mb-0  Generación de calor.  

              p.mb-0  Consumo de combustibles. 

              p.mb-0  Criterios ambientales para la adquisición de insumos y materiales. (+)
    .row.mt-4.justify-content-center
      .col-lg-6
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t3/pdf.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.text-small.mb-0 Para saber más puede consultar:
                  p.text-small.mb-0 Sobreocupación del espacio, entre otros.
                  p.text-small.mb-0 Arboleda J. (2008) Manual EIA. Pág. 20-21


                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 
    p.mt-4 Revise la tabla Aspectos ambientales más comunes en los procesos manufactureros o industriales Manual EIA Jorge Arboleda.
    .row.justify-content-center
      .col-lg-6
        .titulo-sexto.color-acento-contenido
          h5 Tabla 2.
          span Aspectos ambientales más comunes en los procesos manufactureros o industriales Manual EIA Jorge Arboleda
        .tabla-b.color-acento-contenido.mb-5
          .tabla-b__header
            .row
              .col-lg-5
                h4.mb-0 Aspecto

              .col-lg-7
                h4.mb-0 Tipo
          table
            caption Fuente: Jorge Arboleda (2008) Manual EIA. Pág. 20-21.<br>https://drive.google.com/drive/folders/10tRljdtgOmTg404fiXsbQmzjG9sXxxDR

            tr
              th Vertimientos
              td • Aguas de proceso<br>• Aguas de lavado<br>• Aguas domésticas
            tr
              th Emisiones
              td • Material particulado<br>• Gases<br>• Olores ofensivos<br>• Ruido<br>• Calor
            tr
              th Residuos
              td • Residuos aprovechables<br>• Residuos no aprovechables<br>• Residuos peligrosos o especiales
            tr
              th Consumos
              td • Agua<br>• Energía<br>• Materias primas<br>• Combustibles
            tr
              th Peligros
              td • Explosión<br>• Incendio<br>• Derrame (líquidos o sólidos)<br>• Fuga (gases)<br>• Inundación<br>• Accidente vehicular
    .row.mt-5
      .col-lg-4
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Evaluación de Impacto Ambiental (EIA)
    .row.mb-5.mt-4
      .col-sm.mb-5.mb-sm-0
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span 1
            | Se entiende por Evaluación de Impacto Ambiental, el conjunto de estudios y sistemas técnicos que permiten estimar los efectos que la ejecución de un determinado proyecto, obra o actividad, causa sobre el medio ambiente, el cual tiene la identificación de los aspectos e impactos ambientales por medio de metodologías cuantitativas y/o cualitativas como puede ser el desarrollo de matrices de impacto ambiental.  (Vicente Conesa - Guía Metodológica para la Evaluación del Impacto Ambiental).
    .row.justify-content-center.mt-5
      .col-lg-10
        img(src="@/assets/curso/t3/18.png")
    .row.mb-5.mt-4
      .col-sm.mb-5.mb-sm-0
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span 2
            | Por lo tanto la EIA, debe cubrir cada una de las etapas del proyecto, obra o actividad.
    .row.justify-content-center.mt-5
      .col-lg-10
        img(src="@/assets/curso/t3/19.png")      
    .row.mb-5.mt-4
      .col-sm.mb-5.mb-sm-0
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span 3
            | La EIA es el enlace entre la gestión ambiental y la gestión técnica, económica y administrativa que requieren los proyectos. Igualmente, es uno de los instrumentos de gestión de los proyectos que aportan elementos para lograr su viabilidad global.<br><br>Se puede concluir entonces que toda EIA se debe realizar siguiendo secuencialmente cuatro (4) grandes fases o componentes, como se ilustran:
    .row.justify-content-center.mt-5
      .col-lg-8
        img(src="@/assets/curso/t3/20.png")     
    .row.mt-5
      .col-lg-3
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Tipos de impacto ambiental     
    .row.mb-5.mt-4
      .col-sm.mb-5.mb-sm-0
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span 2
            | Los impactos ambientales se derivan de los aspectos ambientales podríamos decir que los aspectos ambientales son las causas en la interacción del hombre con el medio ambiente y el impacto su consecuencia 
    p ejemplos de impacto:
    p.mb-0 Aspecto ambiental: Tala de árboles (causa) y el impacto ambiental (consecuencia) deforestación y desplazamiento de especie.
    p.mb-0 Generación de residuos (causa) y el impacto ambiental (consecuencia) sobrepresión en el relleno sanitario.
    p.mb-0 Generación de emisiones (causa) y el impacto Contaminación del aire (consecuencia)
    p.mb-0 Generación de vertimientos (causa) y el impacto ambiental contaminación del agua (consecuencia).
    .row.justify-content-center.align-items-center.mt-4
      .col-lg-2
        img(src="@/assets/curso/t3/h.svg")     

      .col-lg-6
        .row.p-3.colortt1
          p Para ampliar la información de los aspectos e impactos ambientales puede dirigirse a material de apoyo Manual para la evaluación de impactos ambiental de proyecto, obra o actividad de Jorge Arboleda.

</template>

<script>
export default {
  name: 'Tema3',
  components: {},
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

<style lang="sass">
.tarjeta.color-acento-botones
  background-color: #FFFFFF
.tarjeta--azul
  background-color: #E5EBF8
</style>
