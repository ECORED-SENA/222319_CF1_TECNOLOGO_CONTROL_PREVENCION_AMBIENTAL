<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Identificación de impactos ambientales por ciclo de vida
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/t5/1.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 El ACV Análisis del Ciclo de Vida es una metodología de evaluación de impacto que se usa sobre todo para empresas de producción de productos, que ayuda a identificar por medio de un diagrama de flujo de entradas (insumos) y salidas (productos o residuos de la producción) los diferentes aspectos ambientales generados y la cantidad generada en los mismos si realizamos balances de materia y energía.
    p.mt-4 Para ello, lo invitamos a conocer primero los conceptos básicos:
    separador
    #t_5_1.titulo-segundo.color-acento-contenido
      h2 5.1 Proceso
    p Conjunto de actividades mutuamente relacionadas o que interactúan, las cuales transforman elementos de entrada en resultados ICONTEC (2007) NTC ISO 14040 Gestión Ambiental. Análisis de ciclo de vida, principios y marco de referencia p. 3.
    p Los procesos tienen entradas y salidas:
    .titulo-sexto.color-acento-contenido
      h5 Figura 1.
      span  Esquema Insumos, procesos  y Productos.
    img(src="@/assets/curso/t5/2.png")
    separador
    #t_5_2.titulo-segundo.color-acento-contenido
      h2 5.2 Los diagramas de flujo 
    p De acuerdo con lo que expone Arboleda. (2008) el conceptualiza que los diagramas similares a los de flujo de procesos o los balances de masas o energía, van mostrando en forma secuencial y sistemática la forma como se construye o funciona el proyecto permitiendo identificar fácilmente aquellos puntos donde se presentan actividades que se pueden relacionar con el ambiente, las cuales corresponden a las ASPI (Acciones Susceptibles de Producir Impactos).
    .row.justify-content-center
      .col-lg-10
        img(src="@/assets/curso/t5/3.svg")
        figcaption.mt-2 Tomado de:  Arboleda Jorge Alonso. (2008) Manual para la evaluación de impactos ambiental de proyecto, obra o actividad. p. 24.
    separador
    #t_5_3.titulo-segundo.color-acento-contenido
      h2 5.3 Los aspectos ambientales
    p  De acuerdo con la Norma ISO 14001 define el aspecto ambiental como cualquier elemento de las actividades, productos o servicios de una organización que pueden interactuar recíprocamente con el ambiente, indicando la existencia potencial de un impacto ambiental negativo o positivo.
    p A continuación, podemos ilustrar los aspectos ambientales más comunes en los procesos manufactureros o industriales.
    .row.justify-content-center
      .col-lg-6

        .tabla-b.color-acento-contenido.mb-5
          .tabla-b__header
            .row
              .col-lg-5
                h4.mb-0 Aspecto

              .col-lg-7
                h4.mb-0 Tipo
          table
            caption Tomado de:    Arboleda, Jorge Alonso. (2008) Manual para la evaluación de impactos ambiental de proyecto, obra o actividad. p. 21.
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
    separador
    #t_5_4.titulo-segundo.color-acento-contenido
      h2 5.4 Ciclo de vida del producto 
    p La ISO 14001:2015 define el ciclo de vida como un conjunto de etapas consecutivas e interrelacionadas de un producto o servicio desde el momento en que se obtiene la materia prima hasta que se le entregan al consumidor final.
    p <strong>Por ejemplo:</strong> si por ejemplo si se fabrican pisos de madera, la perspectiva del ciclo de vida tendrá en cuenta todos los riesgos, y posibles impactos ambientales que se produzcan desde la obtención de la materia prima, en este caso la madera, pasando por todas sus etapas de transformación (lijado, barnizado, diseño, ensamblaje…) hasta que llega a manos del consumidor final (incluimos transporte, almacenaje…).
    .row.justify-content-center.mt-5
      .col-lg-6
        .tarjeta.color-primario.p-3.mb-3.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t4/yt.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Ciclo de vida de los productos
                  p.text-small Para consultar más, visualice el siguiente video:
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 
    .row.mt-5
      .col-lg-4
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Apreciación general del ciclo de vida
    p El ACV considera el ciclo de vida completo de un producto, desde la extracción y adquisición de la materia prima, pasando por la producción de energía y materia, y la fabricación, hasta el uso y el tratamiento al final de la vida útil y la disposición final. A través de esta visión general y perspectiva sistemática, se puede identificar y posiblemente evitar el desplazamiento de una carga ambiental potencial entre las etapas del ciclo de vida o los procesos individuales.
    .row.mt-5
      .col-lg-3
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Etapas de un ACV
    p Los estudios de ACV se componen de cuatro etapas:
    .row
      .col-lg-3
        .row.p-2.colort5
          .col-sm.mb-5.mb-sm-0
            ul.lista-ul--color
              li 
                i.fas.fa-check
                | La definición del objetivo y el alcance
      .col-lg-3
        .row.p-2.colort5
          .col-sm.mb-5.mb-sm-0
            ul.lista-ul--color
              li 
                i.fas.fa-check
                | El análisis del inventario
      .col-lg-3
        .row.p-2.colort5
          .col-sm.mb-5.mb-sm-0
            ul.lista-ul--color
              li 
                i.fas.fa-check
                | La evaluación del impacto
      .col-lg-3
        .row.p-2.colort5
          .col-sm.mb-5.mb-sm-0
            ul.lista-ul--color
              li 
                i.fas.fa-check
                | La interpretación
    p.mt-3 El desarrollo de un Análisis de Ciclo de Vida, de acuerdo a la norma ISO 14040, debe cubrir las siguientes etapas metodológicas:
    .row.mt-4
      .col-lg-7
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row.justify-content-center(titulo="Etapa 1 - Definición del Objetivo y Alcance del ACV.")
            .col-md-11
              P En los objetivos se exponen los motivos por los que se desarrolla el estudio, la aplicación prevista y a quién va dirigido. El alcance consiste en la definición de la amplitud, profundidad y detalle del estudio.
          .row.justify-content-center(titulo="Etapa 2 - Análisis de Inventario de Ciclo de Vida.")
            .col-md-11
              P Esta fase incluye la identificación y cuantificación de las entradas (consumo de recursos) y salidas (emisiones al aire, suelo y aguas y generación de residuos) del sistema del producto. Por sistema del producto se entiende el conjunto de procesos unitarios conectados material y energéticamente que realizan una o más funciones idénticas.
          .row.justify-content-center(titulo="Etapa 3 - Evaluación de Impacto de Ciclo de Vida.")
            .col-md-11
              P Durante esta etapa, utilizando los resultados del análisis de inventario, se evalúa la importancia de los potenciales impactos ambientales generados por las entradas y salidas del sistema del producto.
          .row.justify-content-center(titulo="Etapa 4 - Interpretación")
            .col-md-11
              P La cual incluye la combinación de los resultados de las dos etapas anteriores, con la finalidad de extraer, de acuerdo a los objetivos y alcance del estudio, conclusiones y recomendaciones que permitan la toma de decisiones.                                       
      .col-lg-5
        img(src="@/assets/curso/t5/4.png")
    p.mt-4.text-center Escuela de Organización Industrial (2016) Análisis de Ciclo de Vida. p.18.
    .row.justify-content-center.mt-5
      .col-lg-12
        .tarjeta.color-primario.p-3.mb-3.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t4/yt.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Con los siguientes videos se ilustrará de una manera lúdica, como diseñar un análisis del ciclo de vida según la ISO 14040 Análisis del Ciclo de vida
                  p.text-small ClimACT Interreg SUDOE. [CLIMACT]. (2018 Noviembre 20)Analisis de Ciclo de Vida.
                  p.text-small  Investigación Desarrollo e innovación de Estructuras y Materiales. [DAPCO IDIEM]. (s.f).
                  p.text-small Biblioteca del plástico (2016 junio 7) Análisis de Ciclo de Vida.
                
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Ver video
                    i.fas.fa-file-download             
                  .row.mt-2
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Ver video
                        i.fas.fa-file-download   
                  .row.mt-2
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Ver video
                        i.fas.fa-file-download  
    .row.justify-content-center.mt-5
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-3.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t4/drive.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 ¡Estimado Aprendiz!
                  p.text-small Para profundizar en el tema lo invitamos a consultar en MATERIAL DE APOYO / Metodología Análisis del Ciclo de vida ISO 14040.
                  p.text-small  Y se recomienda consultar la norma NTC-ISO 14040-2007 Gestión Ambiental Análisis de Ciclo de vida Principios y Marco de Referencia.

                
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Enlace web
                    i.fas.fa-file-download             
                  .row.mt-2
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Enlace web
                        i.fas.fa-file-download   
    
</template>

<script>
export default {
  name: 'Tema5',
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

<style lang="sass"></style>
