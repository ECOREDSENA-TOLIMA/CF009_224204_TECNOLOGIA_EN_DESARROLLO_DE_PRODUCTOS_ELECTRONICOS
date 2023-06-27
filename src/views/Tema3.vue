<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Métodos de diseño de producto electrónicos
    p(data-aos="fade-down").mb-3 El desarrollo de un producto electrónico debe entenderse como la realización de un proyecto investigativo y como tal debe plantearse teniendo en cuenta una metodología clara que permita identificar un problema o necesidad a solucionar, mediante el planteamiento de objetivos que fijarán la meta y el resultado final del proyecto, tal como se presenta en la figura 8.
    
    .row.mt-3.mb-3
      .titulo-sexto.color-acento-contenido.mb-3.offset-lg-2(data-aos="fade-left")
        p.titulo.pb-0.mb-0 <b>Figura 8.</b> <i>Metodología para el desarrollo de un producto</i>
    
    figure
      img(src='@/assets/curso/temas/tema3/img1.png', alt='Metodología para el desarrollo de un producto')
    .row.justify-content-around.align-items-center.mt-5.mb-3
      TarjetaAudio.col-lg-6.color-acento-contenido.mb-3.tb-6(
        :audio="require('@/assets/componentes/audios/1.mp3')"
        @audio-hover="mostrarIndicadorTarjetaAudio = false"
      )
    p(data-aos="fade-up").mb-5 La verificación y validación en el proceso preliminar al desarrollo de un producto electrónico permite comprobar que las necesidades del cliente se han satisfecho, además de evaluar el potencial mercado que el producto pueda llegar a tener y de esta manera identificar cualquier defecto que deba ser corregido durante la fase desarrollo posterior. Si la respuesta del cliente es mala, el proyecto del desarrollo de un producto electrónico puede terminar, al mismo tiempo que se pueden repetir actividades anteriores, según sea necesario para ajustar el producto e iniciar de nuevo su desarrollo.
    
    .row.mb-3.mt-3
      .titulo-sexto.color-acento-contenido.mb-3.offset-lg-2(data-aos="fade-left")
        p.titulo.pb-0.mb-0 <b>Figura 9.</b> <i>Especificaciones de productos</i>

    .row.justify-content-center.align-items-center.py-0.mb-5(data-aos="fade-right")
      .col-lg-12.col-12.bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img2.svg')})`}"
        )
        .bloque-texto-g__texto.p-4
          p.mb-0 A la hora de definir las características y especificaciones de un producto en general, el equipo desarrollador parte de unos insumos primarios provistos por la actividad de identificación de oportunidades y necesidades de los clientes. De esta primera actividad, se extraen de manera jerárquica y organizada los elementos necesarios para la definición de las especificaciones objetivo.
    
    p(data-aos="fade-left").mb-3 Las especificaciones objetivo dan una descripción precisa de lo que el producto tiene que hacer y son una traducción de las necesidades de los clientes. Las especificaciones objetivo, a través de la fase de desarrollo, se irán madurando hasta obtener las especificaciones finales del producto, las cuales permiten la generación del concepto del producto a desarrollar.
    p(data-aos="fade-right").mb-3 El análisis de todos los posibles entornos y posibles soluciones establecen el siguiente paso en la creación y desarrollo de un producto, permitiendo seleccionar de un mar de posibles soluciones la que mejor se ajuste a las especificaciones del producto final.
    
    .row(data-aos="fade-down").mb-3
      .col-lg-12
        .cajon.color-primario.p-4
          .row.justify-content-around.align-items-center
            .col-sm-1
              img(src="@/assets/curso/temas/tema3/img3.svg")
            .col-lg-11
              p(data-aos="fade-up").mb-3.p-2 Una vez se hayan realizado los ajustes al concepto inicial del producto a través del análisis, la verificación y validación, se definen las especificaciones finales del producto a desarrollar y se inicia con las demás actividades, que forman parte de la maduración del concepto en el desarrollo de un producto electrónico.
    p(data-aos="fade-right").mb-3 Finalmente, los protocolos de atención al cliente tanto interno como externo son herramientas que facilitan la buena comunicación y que permiten que la información suministrada a los clientes se entregue de manera uniforme y sin contratiempos. Por lo tanto, es indispensable para una empresa que exista un protocolo de atención al cliente y que todos sus colaboradores lo conozcan. En el siguiente video se expone todo lo que un protocolo debe contener.
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/M0WqQBa3sRI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video
</template>

<script>
export default {
  name: 'Tema3',
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
