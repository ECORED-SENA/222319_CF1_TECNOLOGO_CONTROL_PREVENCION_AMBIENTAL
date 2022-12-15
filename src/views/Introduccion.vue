<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Presentación Unidad Temática

    img(src="@/assets/curso/intro/1.svg", alt="Texto que describa la imagen")
    .row.mt-5.justify-content-center
      .col-lg-10
        img(src="@/assets/curso/intro/2.svg", alt="Texto que describa la imagen")


</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
