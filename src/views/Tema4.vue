<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Marco normativo ambiental
    separador
    #t_4_1.titulo-segundo.color-acento-contenido
      h2 4.1 La Normativa en Colombia
    p Respetado aprendiz, Las normas que se establecen en Colombia parten del hecho de su importancia y jerarquía en las que involucran derechos y obligaciones establecidas en nuestra constitución política. Es importante conocer que normas y/o leyes prevalecen sobre otras y viceversa, por eso vamos a profundizar en este tema.
    separador
    #t_4_2.titulo-segundo.color-acento-contenido
      h2 4.2 Pero antes pregúntate ¿Qué es ordenamiento Jurídico?
    p En Colombia el derecho se presenta como un sistema jerarquizado de normas que denominamos ordenamiento jurídico. Es así como el ordenamiento jurídico se fundamenta en unas normas de mayor jerarquía que son la Constitución Política o Constitución Nacional, que en Colombia es la expedida por la Asamblea Nacional Constituyente de 1991. 
    .row.justify-content-center
      .col-lg-8
        img(src="@/assets/curso/t4/1.png")
    separador
    #t_4_2.titulo-segundo.color-acento-contenido
      h2 4.2 Pero antes pregúntate ¿Qué es ordenamiento Jurídico?
    p En Colombia el derecho se presenta como un sistema jerarquizado de normas que denominamos ordenamiento jurídico. Es así como el ordenamiento jurídico se fundamenta en unas normas de mayor jerarquía que son la Constitución Política o Constitución Nacional, que en Colombia es la expedida por la Asamblea Nacional Constituyente de 1991. 
    .row.justify-content-center.mt-4.align-items-center
      .col-lg-2
        img(src="@/assets/curso/t3/h.svg")     
      .col-lg-4
        .row.colortt1.p-3
          p Por esta razón la jerarquía de las normas hace que aquellas de rango superior, con la carta fundamental a la cabeza sean la fuente de validez de las que le siguen en dicha escala jerárquica.
          p (FODESEP Rodriguez Jimenez E).
    .row.justify-content-center.mt-5
      .col-lg-8
        .tarjeta.color-primario.p-3.mb-5.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t4/drive.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 ¡Estimado Aprendiz!
                  p.text-small Puede descargar el instructivo de matriz legal aquí.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 
    separador
    #t_4_3.titulo-segundo.color-acento-contenido
      h2 4.3 Marco Normativo Colombiano
    p Para comprender como funcionan las normas en Colombia, hoy entenderemos como se hacen las leyes en nuestro país. En el siguiente video observaremos como funciona nuestro sistema legislativo.
    .row.justify-content-center.mt-5
      .col-lg-6
        .tarjeta.color-primario.p-3.mb-3.mt-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t4/yt.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.text-small Clic en el video para ampliar la información:
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t3/www.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.text-small Las normas más relevantes en materia de legislación ambiental en Colombia las puede consultar en la página web del Ministerio de Medio Ambiente en la pestaña Normatividad.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 
    p En cuanto a normatividad ambiental local con la secretaria distrital de ambiente, áreas metropolitanas o corporaciones autónomas regionales dependiendo del lugar donde se encuentre la organización para que le aplique su jurisdicción.
    separador
    #t_4_4.titulo-segundo.color-acento-contenido
      h2 4.4 ¿Qué es un normograma?   
    p Un normograma es una herramienta en donde se clasifican y jerarquizan las normas que regulan el actuar de diferentes campos y objetos misionales, cuyo propósito es tener la información pertinente para ejecución de estas en un campo o sector determinado, ambientalmente hablando, el normograma ambiental nos ayuda a identificar y clasificar las normas dependiendo el recurso en cuestión ya sea agua, aire, suelo, entre otras.
    .row.justify-content-center
      .col-lg-8    
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t3/www.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.text-small Ejemplo 1: En este enlace se describe un ejemplo de normograma ambiental de la Alcaldia de Mosquera.
                  p.text-small Ejemplo 2: En este link se describe un ejemplo de normograma ambiental del Hospital Rafael Uribe Uribe E.S.E.
                
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
                  .row.mt-3   
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-file-download    
    separador
    #t_4_5.titulo-segundo.color-acento-contenido
      h2 4.5 ¿Qué normas contiene?
    .row.justify-content-center.align-items-center
      .col-lg-2
        img(src="@/assets/curso/t4/m2.svg")     
      .col-lg-4
        .row.p-3.colortt
          p En nuestro caso, el normograma contiene las leyes, decretos, acuerdos, resoluciones que se relacionen directamente con el proyecto, así como también las normas internas, protocolos, manuales, estatutos, y en general aquellos actos administrativos que permitan establecer responsabilidades, obligaciones, funciones, y derechos que deben cumplir todas las organizaciones en nuestro país.
    p.mt-3 Tenga en cuenta, que las normas que incluyen en este formato están encaminadas a dar respuesta a las competencias técnicas que usted ve en la tecnología en control y prevención.
    separador
    #t_4_6.titulo-segundo.color-acento-contenido
      h2 4.6 Autoridades Ambientales en Colombia  
    p Colombia se caracteriza por ser un país con gran diversidad ecológica y ambiental por tal razón, el MINAMBIENTE  Ministerio de Ambiente y Desarrollo sostenible  es el rector y  la máxima autoridad que establece las normas , políticas y la gestión del ambiente y de los recursos naturales renovables , cuyo propósito es el de  orientar y regular el ordenamiento ambiental del territorio, establecer políticas ,regulaciones para el aprovechamiento, manejo y uso  de los recursos naturales renovables y del ambiente de la nación, a fin de asegurar el desarrollo sostenible y el bienestar de ambiental de todos los colombianos.
    .row.justify-content-center
      .col-lg-8    
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t4/yt.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Creación del Ministerio de Ambiente y Desarrollo Sostenible 
                  p.text-small Observemos el siguiente video, que nos ilustra que hace el MINAMBIENTE.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
    p.mt-4 Desde el observatorio de gobernanza del agua en su página web (http://www.ideam.gov.co/web/ocga/autoridades), se puede visualizar el orden jerárquico nacional de autoridades ambientales así: 
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row.justify-content-center(titulo="Ministerio de Ambiente y Desarrollo Sostenible")
        .col-md-3
          img(src='@/assets/curso/t4/2.png', alt='Texto que describa la imagen')
      
        .col-md-7
          p El Ministerio de Ambiente y Desarrollo Sostenible es el rector de la gestión del ambiente y de los recursos naturales renovables.
      .row.justify-content-center(titulo="Autoridad Nacional de Licencias Ambientales")
        .col-md-3
          img(src='@/assets/curso/t4/3.png', alt='Texto que describa la imagen')
      
        .col-md-7
          p Es una Unidad Administrativa Especial, creada mediante el Decreto 3573 del 2011, de orden nacional encargada de que los proyectos, obras o actividades sujetos de licenciamiento, permiso o trámite ambiental cumplan con la normativa, de tal manera que contribuyan al desarrollo sostenible.
      .row.justify-content-center(titulo="Parques Nacionales Naturales de Colombia")
        .col-md-3
          img(src='@/assets/curso/t4/4.png', alt='Texto que describa la imagen')
      
        .col-md-7
          p Es una Unidad Administrativa Especial, creada mediante el Decreto 3572 del 2011, de orden nacional encargada de la administración y manejo del Sistema de Parques Nacionales Naturales y la coordinación del Sistema Nacional de Áreas Protegidas, así como de su administración, control y conservación.
      .row.justify-content-center(titulo="Parques Nacionales Naturales de Colombia")
        .col-md-11
          p Las Corporaciones Autónomas Regionales - CAR son entes corporativos de carácter público, creados por la ley, integrados por las entidades territoriales que por sus características constituyen geográficamente un mismo ecosistema o conforman una unidad geopolítica, biogeográfica o hidro geográfica, dotados de autonomía administrativa y financiera, patrimonio propio y personería jurídica, encargados por la ley de administrar, dentro del área de su jurisdicción el medio ambiente y los recursos naturales renovables y propender por su desarrollo sostenible, de conformidad con las disposiciones legales y las políticas del MADS.
          .row.justify-content-center
            .col-lg-9
              .tarjeta.color-primario.p-3.mb-5
                .row.justify-content-around.align-items-center
                  .col-3.col-sm-2.col-lg-1
                    img(src="@/assets/curso/t3/www.svg")
                  .col
                    .row.justify-content-between.align-items-center
                      .col.mb-3.mb-sm-0
                        p.text-small Visualice la matriz informativa de las corporaciones autónomas regionales y de desarrollo sostenible en el país.
                      .col-sm-auto
                        a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                          span Descargar
                          i.fas.fa-file-download   
      .row.justify-content-center(titulo="Autoridades Ambientales Urbanas")
        .col-md-11
          p Estas instituciones están encargadas de promover y ejecutar programas y políticas nacionales, regionales y sectoriales en relación con el medio ambiente y los recursos naturales renovables -las mismas funciones de las Corporaciones Autónomas Regionales- en los municipios, distritos o áreas metropolitanas cuya población urbana fuere igual o superior a un millón de habitantes
          .row
            .col-sm.mb-5.mb-sm-0
              ul.lista-ul--color
                li 
                  i.fas.fa-check
                  | Departamento Técnico Administrativo del Medio Ambiente de Barranquilla
              ul.lista-ul--color
                li 
                  i.fas.fa-check
                  | Departamento Administrativo Distrital del Medio Ambiente de Santa Marta
              ul.lista-ul--color
                li 
                  i.fas.fa-check
                  | Establecimiento Público Ambiental de Cartagena
              ul.lista-ul--color
                li 
                  i.fas.fa-check
                  | Área Metropolitana del Valle de Aburrá
              ul.lista-ul--color
                li 
                  i.fas.fa-check
                  | Secretaría Distrital de Ambiente de Bogotá
              ul.lista-ul--color
                li 
                  i.fas.fa-check
                  | Departamento Administrativo para Gestión del Medio Ambiente de Cali.
    p.mt-4 ¡Sitios de interés! Para la búsqueda de la información normativa, le sugerimos visitar las siguientes páginas con contenido relacionado:
    .row.justify-content-center
      .col-lg-6
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t3/www.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.text-small Minambiente
                  p.text-small Secretaría Distrital de Ambiente

                  p.text-small CAR

                  p.text-small Foro Nacional Ambiental

                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 
                  .row.mt-2
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-file-download 
                  .row.mt-2
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-file-download 
                  .row.mt-2
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-file-download
    separador
    #t_4_7.titulo-segundo.color-acento-contenido
      h2 4.7 Sistema Nacional Ambiental SINA
    p En Colombia la ley 99 de 1993 creó el Sistema Nacional Ambiental (SINA), que se define como el conjunto de orientaciones, normas, actividades, recursos, programas e instituciones que permiten la puesta en marcha de los principios generales ambientales contenidos en la Constitución Política de Colombia de 1991 y la ley 99 de 1993.
    .row.justify-content-center.align-items-center
      .col-lg-2
        img(src='@/assets/curso/t3/h.svg', alt='Texto que describa la imagen')
      .col-lg-4
        .row.p-3.colortt1
          h4 Sabias que!!!!! 
          p El SINA está integrado por el Ministerio del Medio Ambiente, las Corporaciones Autónomas Regionales, las Entidades Territoriales y los Institutos de Investigación adscritos y vinculados al MINAMBIENTE.
    .row.mt-5
      .col-lg-6
        .row.estilo1.p-2
          h3.text-white.text-center.mb-0 ¿Sabe cuáles son las principales funciones del SINA?
    p.mt-3 El sistema nacional ambiental realiza las siguientes funciones:
    .row
      .col-sm.mb-5.mb-sm-0
        ul.lista-ul--color
          li 
            i.fas.fa-check
            | Dirigir y coordinar el Sistema Nacional Ambiental. -SINA-
          li 
            i.fas.fa-check
            | Apoyar y coordinar los procesos de planificación de las autoridades ambientales
          li 
            i.fas.fa-check
            | Definir y orientar, de acuerdo con las directrices del ministro, las líneas de investigación y estudios ambientales.
          li 
            i.fas.fa-check
            | Orientar y coordinar la creación de espacios y mecanismos para fomentar la coordinación, fortalecimiento, articulación y mutua cooperación de las entidades que integran el Sistema Nacional Ambiental.
          li 
            i.fas.fa-check
            | Solicitar a las autoridades ambientales y demás entidades del Sector la información que se requiera para la formulación de la política ambiental y el seguimiento a la ejecución de sus planes y programas.
          li 
            i.fas.fa-check
            | Definir los aspectos ambientales, para la formulación de las políticas nacionales de población.
          li 
            i.fas.fa-check
            | Brindar orientación a las entidades territoriales.
          li 
            i.fas.fa-check
            | Coordinar con el Viceministerio la formulación e implementación de la política de ordenamiento ambiental del territorio.
          li 
            i.fas.fa-check
            | Proponer las regulaciones ambientales sobre uso del suelo.
          li 
            i.fas.fa-check
            | Emitir conceptos técnicos sobre los planes de ordenamiento territorial de los municipios y distritos.
          li 
            i.fas.fa-check
            | Impartir directrices a las entidades territoriales, sectores económicos y demás agentes productivos, de servicios y del conocimiento en el manejo de los efectos e impactos ambientales de los desastres naturales.
          li 
            i.fas.fa-check
            | Orientar la formulación de la política y los mecanismos para la protección del conocimiento tradicional asociado a la conservación y uso sostenible de la biodiversidad.
          li 
            i.fas.fa-check
            | Dar orientaciones, lineamientos y directrices en educación y participación en materia ambiental.
    .row.justify-content-center.align-items-center

      .col-lg-4
        .row.p-3.colortt1
          p Teniendo en cuenta todas estas funciones que realiza en SINA, vemos la importancia de este organismo en el desarrollo sistémico y organizado para la realidad ambiental en nuestro país. 
      .col-lg-2
        img(src='@/assets/curso/t4/h2.png', alt='Texto que describa la imagen')    
    .row.justify-content-center.mt-4
      .col-lg-8
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t4/yt.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Antioquia conmemoró los 25 años del Sistema Nacional Ambiental
                  p.text-small Visualice el video que muestra lo que se ha realizado a partir de su creación en 1993 y gestión realizada hasta nuestros días:


                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 
    separador
    #t_4_8.titulo-segundo.color-acento-contenido
      h2 4.8 CUMBRES DE LA TIERRA
    p Cumbre de la Tierra es la expresión que se utiliza para denominar las Conferencias de Naciones Unidas (ONU)  sobre el Medio ambiente y su Desarrollo por medio del Programa de las Naciones Unidas para el Medio Ambiente (PNUMA) , un tipo excepcional de encuentro internacional entre jefes de estado de todos los países del mundo, con el fin de alcanzar acuerdos sobre el medio ambiente, desarrollo, cambio climático, biodiversidad y otros temas relacionados.
    .row.justify-content-center.align-items-center
      .col-lg-2
        img(src="@/assets/curso/t4/m2.svg")     
      .col-lg-4
        .row.p-3.colortt
          p La primera Cumbre de la Tierra se realizó en Estocolmo (Suecia), del 5 al 16 de junio de 1972. Veinte años después se realizó la segunda en Río de Janeiro (Brasil), del 2 al 13 de junio de 1992. La tercera se realizó en Johannesburgo (Sudáfrica), del 23 de agosto al 5 de septiembre del 2002. La cuarta cumbre se reunió en junio de 2012 en Río de Janeiro, bajo la denominación de Conferencia de Desarrollo Sostenible Río+20.
    .row.justify-content-center.mt-3
      .col-lg-6
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t3/www.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.text-small Para ampliar la información haga clic en el link:
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 
    p.text-center.mt-4 Haga un alto en este tema y visualice el video propuesto clic en el link:
    .row.justify-content-center.mt-3
      .col-lg-8
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t4/yt.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Objetivos de Desarrollo Sostenible 2030
                  p.text-small Unesco (2017, enero 26 ) Los Objetivos de Desarrollo Sostenible - qué son y cómo alcanzarlos.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download     
    .row.justify-content-center.mt-3
      .col-lg-6
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t4/drive.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 ¡Estimado Aprendiz!
                  p.text-small Para profundizar en el tema lo invitamos a consultar en MATERIAL DE APOYO / Instructivo Matriz legal.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 
</template>

<script>
export default {
  name: 'Tema4',
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
