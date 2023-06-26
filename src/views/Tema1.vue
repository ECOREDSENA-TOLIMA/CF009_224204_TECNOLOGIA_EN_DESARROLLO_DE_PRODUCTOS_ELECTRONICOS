<template lang="pug">
.curso-main-container.pb-3.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Documentación del desarrollo de productos electrónicos 
    p(data-aos="fade-down").mb-3 El desarrollo de cualquier producto involucra a un equipo de trabajo interdisciplinario organizado de tal forma que participen en las diferentes etapas de concepción, diseño, fabricación y producción. Es así como, por cada etapa se genera la documentación respectiva necesaria para llevar a buen término la materialización de una idea.
    .cajon-tema1.color-acento-botones.p-4.p-md-5.mb-5(data-aos="fade-right")
      .row.justify-content-around.align-items-center
        .col-sm-1
          img(src="@/assets/curso/temas/tema1/img1.svg")

        .col-lg-11
          p(data-aos="fade-up").mb-3 La documentación es la evidencia tangible y el insumo primario que sirve de referencia y base para el desarrollo de futuros productos además de permitir la trazabilidad, el control de versiones y modificaciones del producto que sean necesarias.
    p(data-aos="fade-down").mb-3 A través de la documentación se consignan datos e información relevante del proyecto, tales como la elaboración de: cálculos, diagramas eléctricos y electrónicos, lista de materiales (BOM list), entre otras. Esta misma información puede ser insumo para la elaboración de otra documentación como por ejemplo los manuales de usuario y de servicio técnico, que respaldan la finalidad prevista del producto electrónico elaborado.
    
    .row.mb-3
      .titulo-sexto.color-acento-contenido.mb-3.offset-lg-2(data-aos="fade-left")
        p.titulo.pb-0.mb-0 <b>Figura 2.</b> <i>Uso de encuestas en el desarrollo de productos</i>
    
    
    .row.justify-content-center.align-items-center.py-0.mb-5(data-aos="fade-right")
      .col-lg-12.col-12.bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img2.svg')})`}"
        )
        .bloque-texto-g__texto.p-4
          p.mb-0 Las encuestas son un tipo de documentación que permite establecer oportunidades mediante la recolección de información e identificación de necesidades latentes en el mercado para el desarrollo de un nuevo producto.
    
    p.mb-0 Dentro de la documentación técnica generada en el desarrollo de productos electrónicos se destacan los derivados de la etapa de diseño y producción; planos esquemáticos, lista de materiales, dibujo mecánico, archivos de fabricación electrónica y mecánica, archivos de ensamble electrónico y mecánico entre otros. La elaboración de esta documentación se realiza mediante <em>software</em> especializado CAD/CAM que facilita el proceso. A continuación se explica brevemente la documentación técnica más relevante en procesos de desarrollo de productos electrónicos.
    br
    TabsA.color-acento-contenido(data-aos="fade-right")
            .tarjeta.color-acento-contenido--borde.p-5(titulo="Orden de trabajo")
              h3 Orden de trabajo
              p.mb-0 Las órdenes de trabajo representan el paso preliminar a la elaboración y ejecución de una tarea. Son documentos que contienen los lineamientos, especificaciones y orientaciones a tener en cuenta para la realización de una actividad. 
              br
              p.mb-0 Cuando se habla de una orden de trabajo en procesos de diseño electrónico estas deben contener descritas las tareas y especificaciones del proceso a realizar. Se elabora a mano o digitalmente.
            .tarjeta.color-acento-contenido--borde.p-4(titulo="Planos esquemáticos")
              h3 Planos esquemáticos
              p.mb-0 Son representaciones gráficas de los circuitos electrónicos. Se realizan a partir de los símbolos de los componentes electrónicos que formarán parte del circuito. 
              br
              p.mb-0 En otras palabras, un plano esquemático es un dibujo elaborado a partir de la simbología de los componentes electrónicos que permiten su análisis e interpretación funcional.
              br
              p.mb-0 Se elaboran mediante un software de diseño asistido por computador aunque también se pueden elaborar a mano.
            .tarjeta.color-acento-contenido--borde.p-4(titulo="Lista de materiales (BOM list)")
              h3 Lista de materiales (BOM list)
              p.mb-0 La lista de materiales electrónicos es un documento técnico necesario para el ensamble de la tarjeta electrónica; sirve además de insumo para la compra de los materiales.
              br
              p.mb-0 Se elaboran mediante un <em>software</em> de diseño asistido por computador o mediante registro manual. En el documento se describen los consecutivos, las cantidades y las características de cada componente electrónico necesario para el correcto funcionamiento de la tarjeta electrónica.
            .tarjeta.color-acento-contenido--borde.p-4(titulo="Geber files (Archivos de fabricación)")
              h3 <em>Geber files</em> (Archivos de fabricación)
              p.mb-0 Son documentos que contienen los artes gráficos necesarios para la fabricación de la placa de circuito impreso, incluyen el trazado de pistas eléctricas y los <em>footprints</em> de los componentes electrónicos.
              br
              p.mb-0 Se elaboran mediante un <em>software</em> de diseño asistido por computador.
            .tarjeta.color-acento-contenido--borde.p-4(titulo="Planos Mecánicos")
              h3 Planos mecánicos
              p.mb-0 Son documentos técnicos de la pieza diseñada, como por ejemplo la documentación gráfica necesaria para la fabricación de los elementos mecánicos en máquinas de control numérico y centros de mecanizado; adicionalmente, forma parte de dicha documentación técnica los planos de despiece y ensamble, planos de vistas 2D y 3D.
              br
              p.mb-0 Se elaboran mediante <em>software</em> asistido por computador y software CAM (Fabricación asistida por computador).
            .tarjeta.color-acento-contenido--borde.p-4(titulo="Manuales de servicio")
              h3 Manuales de servicio
              p.mb-0 Es un documento elaborado a partir de otros documentos técnicos (planos esquemáticos, planos mecánicos de ensamble, entre otros). Adicionalmente incluye información asociada al proceso de mantenimiento del producto electrónico.
              br
              p.mb-0 Los manuales de servicio se elaboran reuniendo documentos técnicos necesarios para definir criterios de mantenimiento y reparación del producto electrónico.
    br
    p(data-aos="fade-down").mb-5 El primer paso en el desarrollo de un producto electrónico inicia con la identificación de las necesidades y oportunidades latentes en el mercado, permitiendo establecer los requerimientos iniciales para desarrollar un nuevo producto electrónico. En esta fase del proceso se realiza una recolección de información mediante el área de mercadeo.
    .col-lg-12(data-aos="fade-up")
        .bloque-texto-c.cajon-tema1.color-primario.p-4
          i.fas.fa-quote-right
          h4.mb-2 Las especificaciones dan una descripción precisa de lo que el producto tiene que hacer. Son la traducción de las necesidades del cliente en términos técnicos. Los objetivos de las especificaciones se establecen claramente en el proceso y representan las expectativas del equipo de desarrollo.” 
          span - (Ulrich, K. T, 2013).
    br      
    p(data-aos="fade-down").mb-5 Es importante que la definición de los requerimientos del producto a desarrollar sea clara. La siguiente figura 3 presenta un procedimiento sugerido para la definición de los requerimientos.
    .row.justify-content-center.align-items-center
      .col-lg-10(data-aos="fade-down")
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 3. Procedimiento de definición de requerimientos
        figure
          img(src='@/assets/curso/temas/tema1/img3.jpg', alt='Procedimiento para definición de requerimientos')
</template>

<script>
export default {
  name: 'Tema1',
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
