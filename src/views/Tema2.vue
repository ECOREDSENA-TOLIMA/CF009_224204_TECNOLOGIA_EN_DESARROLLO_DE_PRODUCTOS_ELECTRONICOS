<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Arquitectura de productos electrónicos
    p(data-aos="fade-down").mb-5 Los productos electrónicos se desarrollan con una finalidad prevista determinada por el fabricante y teniendo en cuenta la necesidad que se desea atender, por lo tanto, su arquitectura varía en función a ello. Los productos electrónicos se encuentran en diferentes áreas y sectores de la economía; la educación, la domótica, las telecomunicaciones, el control industrial, la medicina son algunos ejemplos.
    .row.justify-content-center.align-items-center.py-0.mb-5(data-aos="fade-right")
      .col-lg-12.col-12.bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img1.svg')})`}"
        )
        .bloque-texto-g__texto.p-4
          p.mb-0 La definición y estructuración de la arquitectura de un producto electrónico está sujeto a las diferentes normas de producto que regulan los mercados, garantizando por un lado que se fabriquen con calidad y cumpliendo estándares y, por otra parte, que el producto elaborado no represente un potencial peligro para quien lo utilice.
    .row 
      .col-lg-7
        p(data-aos="fade-down").mb-5 Cada empresa desarrolladora de productos electrónicos debe tomar dos importantes decisiones en la definición de la arquitectura de su producto, la primera tiene que ver con la definición del proceso de diseño es decir cómo lo quiere hacer, y la segunda hace referencia a cómo organizará su equipo de trabajo para llevar a feliz término el desarrollo de ese producto.
        p(data-aos="fade-left").mb-5 Ahora bien, para que los productos electrónicos sean competitivos en un mercado globalizado deben cumplir con normativa técnica relacionada con las características del mismo, mediante la cual un producto accede a un mercado, ya que esta le permite apegarse a las condiciones mínimas de seguridad requeridas para su operación y funcionamiento.
        p(data-aos="fade-right").mb-5 Lo anterior se ve reflejado en las normas de compatibilidad electromagnética las cuales, en la mayoría de los países, son de obligatorio cumplimiento para los diferentes productos electrónicos que se desean fabricar y comercializar. Estas normas se encargan, entre otras cosas, de establecer los límites para que las radiaciones electromagnéticas no sean nocivas para los seres vivos y el medio ambiente.
      .col-lg-5(data-aos="fade-up")
        figure
          img(src='@/assets/curso/temas/tema2/img2.svg').m-auto
    .row(data-aos="fade-down")
      .col-lg-12
        .cajon.color-acento-contenido.p-4
          .row.justify-content-around.align-items-center
            .col-sm-1
              img(src="@/assets/curso/temas/tema2/img3.svg")
            .col-lg-11
              p(data-aos="fade-up").mb-3.p-2 Las normas IPC, por su parte, permiten estandarizar procesos de diseño, ensamble y hasta de soldadura en tarjetas de circuito impreso, garantizando criterios de calidad y aceptabilidad.
    br
    p(data-aos="fade-down").mb-5 Los productos electrónicos se desarrollan con una finalidad prevista determinada por el fabricante y teniendo en cuenta la necesidad que se desea atender, por lo tanto, su arquitectura varía en función a ello. Los productos electrónicos se encuentran en diferentes áreas y sectores de la economía; la educación, la domótica, las telecomunicaciones, el control industrial, la medicina son algunos ejemplos. 

    .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-md-5(data-aos="fade-up")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img4.svg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 En la fabricación de circuitos impresos, por ejemplo, el tamaño de las pistas conductoras limita las capacidades de fabricación ya que el proceso mismo implica una mayor precisión y detalle cuando se requieren tamaños y espacios entre los elementos conductores mucho más pequeños.
    br
    p(data-aos="fade-down").mb-5 De igual manera sucede con el número de capas en una tarjeta electrónica (planos de pistas conductoras que sirven para interconectar los componentes electrónicos dentro de una tarjeta electrónica) cuando se requiere de más de dos capas el proceso se puede ver limitado a nivel local y es posible se tenga que recurrir a un fabricante internacional que esté en la capacidad de hacerlo. En la siguiente figura 2 se puede apreciar los elementos que conforman una placa de circuito impreso.
    .row.justify-content-center.align-items-center
      .col-lg-10(data-aos="fade-up")
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 2. Estructura de una placa de circuito impreso
        figure
          img(src='@/assets/curso/temas/tema2/img5.jpg', alt='Estructura de una placa de circuito impreso')
          figcaption Nota. Tomado de Microensamble (2014).
    br
    p(data-aos="fade-up").mb-5 A nivel mecánico las limitaciones igualmente están dadas por los <b>requerimientos especiales de la pieza mecánica a desarrollar</b>, las cuales se pueden ver afectadas por las especificidades particulares para el manejo de un material; fabricar una pieza mediante un proceso termo formado es mucho más sencillo y económico que hacerlo por un proceso de inyección de plástico.
    .row(data-aos="fade-down")
      .col-lg-12
        .cajon.color-primario.p-4
          .row.justify-content-around.align-items-center
            .col-sm-1
              img(src="@/assets/curso/temas/tema2/img6.svg")
            .col-lg-11
              p(data-aos="fade-up").mb-3.p-2 En otras palabras, el desarrollo de un producto electrónico estará sujeto a los costos del proceso, la tecnología empleada, los materiales usados, las dimensiones y tamaños físicos e incluso los requerimientos normativos de cada producto limitando su diseño y fabricación.
</template>

<script>
export default {
  name: 'Tema2',
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
