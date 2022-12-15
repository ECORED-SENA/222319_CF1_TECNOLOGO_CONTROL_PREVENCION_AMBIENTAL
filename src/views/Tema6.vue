<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Métodos e instrumentos para la recolección de la información
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/t6/1.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 Los métodos y técnicas de recolección de datos pueden dividirse en dos categorías: métodos primarios de recolección de datos y métodos secundarios de recolección de datos.
    separador
    #t_6_1.titulo-segundo.color-acento-contenido
      h2 6.1 Métodos de recolección de datos primarios
    p.mb-0 Los datos primarios se recolectan de la experiencia de primera mano y no se utilizan en el pasado. Esta información es específica, altamente auténtica y precisa.
    p Los métodos de recolección de datos primarios pueden dividirse en dos categorías: métodos cuantitativos y métodos cualitativos.
    .row.mt-5
      .col-lg-3
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Métodos cuantitativos
    p.mt-3 Los métodos cuantitativos para la investigación de mercados y la previsión de la demanda suelen utilizar herramientas estadísticas. Aquí, la demanda se pronostica sobre la base de datos históricos.
    p Estos métodos y técnicas de recolección de datos primarios se utilizan generalmente para hacer pronósticos a largo plazo. Son altamente confiables, ya que el elemento de subjetividad es mínimo.
    TabsA.color-acento-contenido.mb-5

      .tarjeta.color-acento-contenido--borde.p-4(titulo="Análisis de series cronológicas o temporales")
        h4 Análisis de series cronológicas o temporales
        p El término se refiere a un orden secuencial de valores de una variable, conocido como tendencia a intervalos de tiempo iguales. Utilizando tendencias, una organización puede predecir la demanda de sus productos y servicios para el tiempo proyectado. 
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Técnicas de suavizado")
        h4 Técnicas de suavizado
        p En los casos en que la serie temporal carece de tendencias significativas, se pueden utilizar técnicas de suavizado para eliminar una variación aleatoria de la demanda histórica. Esto ayuda a identificar patrones y niveles de demanda que pueden ser usados para estimar la demanda futura.
        p Los métodos más comunes utilizados en las técnicas de suavizado de la previsión de la demanda son el método de media móvil simple y el método de media móvil ponderada.
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Método Barométrico")
        h4 Método Barométrico
        p También conocido como el enfoque de los indicadores principales, este método se utiliza para especular sobre las tendencias futuras en función de la evolución actual. 

        p Cuando un evento pasado se considera para predecir el evento futuro, el evento pasado actuaría como un indicador principal.
    .row.mt-5
      .col-lg-3
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 Métodos cualitativos
    .row.justify-content-center.align-items-center
      .col-lg-4.mt-4
        .row.p-3.colortt1
          p Los métodos de recolección de datos cualitativos son especialmente útiles en situaciones en las que no se dispone de datos históricos, no se necesitan números ni cálculos matemáticos.
        .row.p-3.colortt1.mt-3
          p La investigación cualitativa está estrechamente relacionada con palabras, sonidos, sentimientos, emociones, colores y otros elementos que no son cuantificables.      
      .col-lg-4.mt-4
        img.wi1(src="@/assets/curso/t6/2.svg")

      .col-lg-4.mt-4
        .row.p-3.colortt1
          p Estas técnicas se basan en la experiencia, el juicio, la intuición, las conjeturas, las emociones, etc.
        
        .row.p-3.colortt1.mt-3
          p Los métodos y técnicas de recolección de datos cuantitativos no proporcionan el motivo de las respuestas de los participantes, a menudo no llegan a las poblaciones subrepresentadas y pueden abarcar largos períodos de tiempo para recopilar los datos. Por lo tanto, es mejor combinar métodos cuantitativos con métodos cualitativos.
    p.text-center.mt-4 En la infografía encontrará algunos de los métodos de recolección de datos cualitativos, explórelos:
    h4 Encuestas:
    p Las encuestas se utilizan para recopilar datos de la audiencia objetivo y recoger información sobre sus preferencias, opiniones, elecciones y comentarios relacionados con tus productos y servicios.
    p La mayoría de los programas de creación de encuestas a menudo ofrecen una amplia gama de tipos de preguntas para seleccionar.
    p También puedes utilizar una plantilla de encuesta ya preparada para ahorrar tiempo y esfuerzo. Las encuestas en línea se pueden personalizar según la marca de la empresa cambiando el tema, el logotipo, etc. 
    p Existen diversos métodos de distribución de encuestas, como vía correo electrónico, sitio web, aplicación offline, código QR, redes sociales, etc. Dependiendo del tipo y la fuente de su audiencia, puede seleccionar el canal.
    p Un panel de encuestas puede proporcionar estadísticas relacionadas con la tasa de respuesta, la tasa de finalización, los filtros basados en la demografía, las opciones de exportación y uso compartido, etc.
    p Una vez recopilados los datos, el software para encuestas puede generar varios tipos de informes y ejecutar algoritmos analíticos para descubrir información oculta. 
    TabsC.color-acento-contenido
      .py-3.py-md-4(titulo="Encuestas")
        .row
          .col-md-1
          .col-md-3.mb-4.mb-md-0
            img(src='@/assets/curso/t6/3.png', alt='Texto que describa la imagen')
          .col-md-7
            h4 Encuestas
            p.mb-0 Las encuestas se utilizan para recopilar datos de la audiencia objetivo y recoger información sobre sus preferencias, opiniones, elecciones y comentarios relacionados con tus productos y servicios.
            p La mayoría de los programas de creación de encuestas a menudo ofrecen una amplia gama de tipos de preguntas para seleccionar.
            p También puedes utilizar una plantilla de encuesta ya preparada para ahorrar tiempo y esfuerzo. Las encuestas en línea se pueden personalizar según la marca de la empresa cambiando el tema, el logotipo, etc. 
            p Existen diversos métodos de distribución de encuestas, como vía correo electrónico, sitio web, aplicación offline, código QR, redes sociales, etc. Dependiendo del tipo y la fuente de su audiencia, puede seleccionar el canal.
            p Un panel de encuestas puede proporcionar estadísticas relacionadas con la tasa de respuesta, la tasa de finalización, los filtros basados en la demografía, las opciones de exportación y uso compartido, etc.
            p Una vez recopilados los datos, el software para encuestas puede generar varios tipos de informes y ejecutar algoritmos analíticos para descubrir información oculta.
      .py-3.py-md-4(titulo="Sondeos")
        .row
          .col-md-1
          .col-md-5.mb-4.mb-md-0
            img(src='@/assets/curso/t6/4.png', alt='Texto que describa la imagen')
          .col-md-5
            h4 Sondeos
            p Los sondeos se componen de una pregunta de opción única o múltiple. Cuando se requiere tener un pulso rápido de los sentimientos de la audiencia, puedes ir a las encuestas. Debido a que son de corta duración, es más fácil obtener respuestas de la gente.
            p También se pueden integrar en varias plataformas. Una vez que los encuestados responden a la pregunta, también se les puede mostrar cómo se encuentran en comparación con las respuestas de los demás.
      .py-3.py-md-4(titulo="Entrevistas")
        .row
          .col-md-1
          .col-md-5.mb-4.mb-md-0
            img(src='@/assets/curso/t6/5.png', alt='Texto que describa la imagen')
          .col-md-5
            h4 Entrevistas
            p En este método, el entrevistador hace preguntas cara a cara o por teléfono a los encuestados. En las entrevistas cara a cara, el entrevistador hace una serie de preguntas al entrevistado en persona y anota las respuestas. 
            p En caso de que no sea posible conocer a la persona, el entrevistador puede apoyarse en una entrevista telefónica.
            p A diferencia de los otros métodos de recolección de datos, este es adecuado cuando sólo hay unos pocos encuestados. Es demasiado largo y tedioso repetir el mismo proceso si hay muchos participantes.
      .py-3.py-md-4(titulo="Técnica Delphi ")
        .row
          .col-md-1
          .col-md-5.mb-4.mb-md-0
            img(src='@/assets/curso/t6/6.png', alt='Texto que describa la imagen')
          .col-md-5
            h4 Técnica Delphi 
            p En él, los expertos del mercado reciben las estimaciones y suposiciones de los pronósticos realizados por otros expertos de la industria. Pueden reconsiderar y revisar sus propias estimaciones e hipótesis sobre la base de la información proporcionada.
      .py-3.py-md-4(titulo="Focus Group ")
        .row
          .col-md-1
          .col-md-5.mb-4.mb-md-0
            img(src='@/assets/curso/t6/7.png', alt='Texto que describa la imagen')
          .col-md-5
            h4 Focus Group
            p.mb-0 Es otro de los métodos y técnicas de recolección de datos en donde un pequeño grupo de personas, alrededor de 8-10 miembros, se reúnen para discutir las áreas comunes del problema con un moderador que regula la discusión. 
            p Cada participante aporta sus puntos de vista sobre el tema en cuestión. Al final de la discusión, el grupo llega a un consenso.
      .py-3.py-md-4(titulo="Cuestionario ")
        .row
          .col-md-1
          .col-md-5.mb-4.mb-md-0
            img(src='@/assets/curso/t6/8.png', alt='Texto que describa la imagen')
          .col-md-5
            h4 Cuestionario
            p Un cuestionario es un conjunto impreso de preguntas, abiertas o cerradas, que los encuestados deben responder en función de sus conocimientos y experiencia con el tema.
            p El cuestionario es parte de la encuesta, mientras que el objetivo final de un cuestionario puede o no ser una encuesta.               
    separador
    #t_6_2.titulo-segundo.color-acento-contenido
      h2 6.2 Métodos y técnicas de recolección de datos secundarias
    p La selección y elaboración de instrumentos de recolección de información es fundamental en el proceso de trabajo comunitario, es el elemento que reúne toda la información previa de una investigación, dando directrices y siendo el marco de referencia para el planteamiento de acciones con la comunidad.
    p Dentro de los instrumentos básicos para la recolección de información, se encuentran, según Cerda (1991), que es uno de los investigadores más reconocidos a nivel mundial y cuyas premisas siguen vigentes, los siguientes:
    .row.mt-4
      .col-lg-2
        img(src='@/assets/curso/t6/h33.svg', alt='Texto que describa la imagen')

      .col-lg-8
        .row.p-3.colorazul
          p.text-white Los métodos y técnicas de recolección de datos secundarios son los datos que se han utilizado en el pasado. El investigador puede obtener datos de las fuentes tanto internas como externas a la organización. 
        .row.justify-content-center
          .col-lg-6.mt-2
            .row.p-3.colortt1
              h5.mb-0 Fuentes internas de datos secundarios:
              p.mb-0 ●	Registros 
              p.mb-0 ●	Estados Financieros

              p.mb-0 ●	Revistas

              p.mb-0 ●	Informes 

              p.mb-0 ●	Resúmenes ejecutivos
          .col-lg-6.mt-2
            .row.p-3.colortt
              h5.mb-0 Fuentes externas de datos secundarios:

              p.mb-0 ●	Informes de los gobiernos

              p.mb-0 ●	Comunicados de prensa


              p.mb-0 ●	Revistas de negocios


              p.mb-0 ●	Bibliotecas


              p.mb-0 ●	Internet
        
      .col-lg-2
        img(src='@/assets/curso/t6/m33.svg', alt='Texto que describa la imagen')
    .row.mt-4
      .col-lg-6
        .row.p-3.colortt1
          p La recolección de datos secundarios también puede incluir técnicas cuantitativas y cualitativas. Estos se encuentran fácilmente disponibles y, por lo tanto, son menos lentos y caros en comparación con los datos primarios. 
      .col-lg-6
        .row.p-3.colortt
          p Sin embargo, en el caso de los métodos secundarios de recogida de datos, no se puede verificar la autenticidad de los datos recogidos.
    .row.justify-content-center.mt-4
      .col-lg-8    
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t3/www.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.text-small Tomado de: QuestionPro (s,f)¿Cuáles son los métodos y técnicas de recolección de datos más efectivos?
                  p.text-small Por tanto, lo invitamos a visualizar el siguiente video: SENA línea Produccion5 (2014, Julio 10). Recolección de Información.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
                  .row.mt-3   
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-file-download    
    .row.justify-content-center.mt-4
      .col-lg-6
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t4/drive.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 ¡Estimado Aprendiz!
                  p.text-small Para profundizar en el tema lo invitamos a consultar en MATERIAL DE APOYO / Instructivo Tabulación y análisis de la información.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Enlace web
                    i.fas.fa-file-download

</template>

<script>
export default {
  name: 'Tema6',
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
