<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-12
        figure
          img(src='@/assets/curso/intro/img1.svg').m-auto
    .row.justify-content-center 
      .col 
        p(data-aos="fade-left").mb-0 Durante todo el proceso de desarrollo de un producto electrónico, además de las tareas técnicas involucradas, existe de por medio un elemento fundamental llamado documentación, el cual juega un papel muy importante ya que permite tener el control de la información que se genera en cada etapa del proceso, al mismo tiempo que sirve de soporte literario y gráfico cuando se requiere (manuales de usuario, documentos de ensamble, dibujo mecánico, entre otros).
        br
    .row.justify-content-center.align-items-center.py-0.mb-5(data-aos="fade-right")
      .col-lg-12.col-12.bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/intro/img2.svg')})`}"
        )
        .bloque-texto-g__texto.p-4
          p.mb-0 Por tal razón para una empresa es importante tener bien organizada y gestionada la información y documentación, ya que representa su bien intangible más valioso y en la mayoría de los casos hace parte del <i>know how</i> de la misma.
    br
    p(data-aos="fade-down").mb-0 Cada etapa involucrada en el proceso de diseño y desarrollo de un producto electrónico genera documentación muy variada, por ejemplo en la etapa de diagramación de la placa de circuito impreso se pueden obtener archivos esquemáticos, lista de materiales, archivos de fabricación, entre otros, mientras que en la etapa de modelamiento mecánico los archivos que se pueden obtener son planos mecánicos y estructurales, archivos de fabricación mecánica, entre otros. 
    br
    p(data-aos="fade-up").mb-0 A continuación se pueden observar diferentes tipos de documentos presentes en el desarrollo de un producto electrónico.
    br
    .tarjeta.tarjeta-gris.p-4.mb-5(data-aos="fade-right") 
      SlyderA(tipo="b")
        .row.justify-content-center.mt-3
          .col-lg-4.mb-4.mb-md-0.my-3
            h4 Plano mecánico
          .col-lg-7.my-3
            img.img-a.img-t(src='@/assets/curso/intro/img3.svg', alt='')      
        .row.justify-content-center.mt-3
          .col-lg-4.mb-4.mb-md-0.my-3
            h4 Órden de trabajo
          .col-lg-7.my-3
            img.img-a.img-t(src='@/assets/curso/intro/img4.svg', alt='') 
        .row.justify-content-center.mt-3
          .col-lg-4.mb-4.mb-md-0.my-3
            h4 Encuestas
          .col-lg-7.my-3
            img.img-a.img-t(src='@/assets/curso/intro/img5.svg', alt='')      
        .row.justify-content-center.mt-3
          .col-lg-4.mb-4.mb-md-0.my-3
            h4 Lista de materiales
          .col-lg-7.my-3
            img.img-a.img-t(src='@/assets/curso/intro/img6.svg', alt='')  
        .row.justify-content-center.mt-3
          .col-lg-4.mb-4.mb-md-0.my-3
            h4 Plano esquemático  
          .col-lg-7.my-3
            img.img-a.img-t(src='@/assets/curso/intro/img7.svg', alt='')      
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
