<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Introducción medio ambiente e impacto ambiental
    p Respetado aprendiz bienvenido a al tema de introducción medio ambiente e impacto ambiental
    img(src="@/assets/curso/t2/1.jpg", alt="Texto que describa la imagen")
    img.mt-3(src="@/assets/curso/t2/2.svg", alt="Texto que describa la imagen")
    .row.justify-content-center.mt-5
      .col-lg-8
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/t2/yt.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 El impacto Ambiental del Hombre
                  p.text-small Lo invitamos a visualizar el siguiente video documental “El impacto Ambiental del Hombre”. National Geographic (2015, Noviembre 26) El impacto ambiental del hombre 2007 (completo).
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

</template>

<script>
export default {
  name: 'Tema2',
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
