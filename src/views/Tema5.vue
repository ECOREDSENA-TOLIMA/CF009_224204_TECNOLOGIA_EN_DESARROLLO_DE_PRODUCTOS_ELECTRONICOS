<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Procesos en la industria electrónica
  .row.justify-content-center.mt-5
    .col-7
      p La electrónica se caracteriza por ser una de las ciencias más transversales de hoy en día; encontrándose en la mayoría de disciplinas y sectores industriales y económicos de un país, por lo tanto, en la industria electrónica se pueden identificar tres grandes fases que permiten su constante innovación: 
      ul.lista-ul--color.ps-3
        li
          i.fas.fa-angle-right.txt
          | Producción de componentes activos y pasivos.
        li
          i.fas.fa-angle-right.txt
          | Producción de software.
        li
          i.fas.fa-angle-right.txt
          | Producción de productos electrónicos terminados.
      p Para el caso de los diseñadores de productos electrónicos, es importante tener en cuenta la siguiente ficha de marketing propuesta por Sarraipa, J., Artífcie, A, Jiménez, H. (2019), en el documento “metodología de evaluación de prototipo innovador”, ver figura 7.
          
    .col-3(data-aos="zoom-in")
      figure
       img(src="@/assets/curso/temas/tema4/img5.svg", alt="alt", style="width:450px;").m-auto
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
