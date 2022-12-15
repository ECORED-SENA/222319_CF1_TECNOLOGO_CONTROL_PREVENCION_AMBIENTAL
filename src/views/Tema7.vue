<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 7
      h1 Diagnóstico ambiental
    p Si una empresa aspira a ser responsable, el primer paso es ser consecuente con los impactos de su actividad en el medio ambiente y en la sociedad.
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/t7/1.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 La gestión ambiental implica la integración de las preocupaciones medioambientales en la toma de decisiones y en las operaciones de la organización. Para ello es necesario el compromiso de la dirección, la medición y evaluación de impactos, el desarrollo de procesos y productos respetuosos con el entorno, y el diálogo y la sensibilización con iniciativas que promuevan la sostenibilidad.

          br
          br
          | Pero antes de todo esto, y para poder avanzar en la mencionada gestión ambiental de la empresa, es indispensable realizar un diagnóstico ambiental preliminar.
    AcordionA.mb-5.mt-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row.justify-content-center(titulo="Conocer e interpretar su impacto ambiental")
        .col-lg-11
          p A partir de este diagnóstico ambiental, la organización podrá conocer e interpretar su impacto ambiental y determinar si sus actuaciones son o no aceptables desde este punto de vista, Pero ¿qué obtiene la organización con esta evaluación ambiental inicial? Aquí hay algunos beneficios:
          p.mb-0 ●	Permite conocer su desempeño medioambiental, tanto las prácticas como los procedimientos existentes relacionados con la gestión ambiental
          p.mb-0 ●	Determina los impactos directos e indirectos, y posibilita la medición del beneficio o el perjuicio de estos
          p.mb-0 ●	Ayuda a localizar las causas de los impactos y los agentes implicados
          p.mb-0 ●	Permite detectar áreas de mejora y definir las posibilidades para intervenir
          p.mb-0 ●	Asigna la responsabilidad de los impactos y la capacidad de influencia
          p.mb-0 ●	Determina la percepción del problema por parte de los implicados y la disposición de éstos para participar en su solución
          p.mb-0 ●	Detecta riesgos, amenazas y oportunidades
          p.mb-0 ●	Evalúa el coste de los impactos y el de las medidas para evitarlos o mitigarlos
          p.mb-0 ●	Comprueba que se está cumpliendo con la legislación y la normativa aplicable
      .row.justify-content-center(titulo="Aspectos genéricos")
        .col-lg-11
          .row
            .col-lg-6
              p Existe una serie de aspectos genéricos que se evalúan en todo diagnóstico ambiental, como el consumo de materias primas, energía y agua, las emisiones de contaminantes y la generación de residuos, a los que la empresa puede añadir otros problemas específicos de su actividad.
              .tarjeta.color-primario.p-3.mb-5
                .row.justify-content-around.align-items-center
                  .col-3.col-sm-2.col-lg-1
                    img(src="@/assets/curso/t3/www.svg")
                  .col
                    .row.justify-content-between.align-items-center
                      .col.mb-3.mb-sm-0
                        p.text-small Estévez, R. (2017, Julio 13). El diagnóstico ambiental en la

                        p.text-small empresa responsable.
                      .col-sm-auto
                        a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                          span Enlace web
                          i.fas.fa-file-download
            
            .col-lg-6
              img(src="@/assets/curso/t7/2.png")
      .row.justify-content-center(titulo="Documento diagnóstico ambiental")
        .col-lg-11
          .row
            .col-lg-6
              p Un documento diagnóstico ambiental en una organización como mínimo debe tener lo siguiente:
              p.mb-0 ●	Características del sistema socio ecológico que rodea la empresa, descripción de los componentes ambientales y su afectación.
              p.mb-0 ●	Descripción de la organización proyecto y análisis del ciclo de vida de donde se identifiquen los aspectos ambientales significativos.

              p.mb-0 ●	Identificación de los requisitos legales ambientales que aplica a la organización.

              p.mb-0 ●	Conclusiones del diagnóstico.

            
            .col-lg-6
              img(src="@/assets/curso/t7/2.png")
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
                  p.text-small Para profundizar en el tema lo invitamos a consultar en MATERIAL DE APOYO Instructivo Informe Diagnóstico Ambiental.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Enlace web
                    i.fas.fa-file-download

</template>

<script>
export default {
  name: 'Tema7',
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
