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
    
    .row.mb-3
      .titulo-sexto.color-acento-contenido.mb-3.offset-lg-2(data-aos="fade-left")
        p.titulo.pb-0.mb-0 <b>Figura 1.</b> <i>Importancia de la gestión de información empresarial</i>
    
    .row.justify-content-center.align-items-center.py-0.mb-5(data-aos="fade-right")
      .col-lg-12.col-12.bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/intro/img2.svg')})`}"
        )
        .bloque-texto-g__texto.p-4
          p.mb-0 Por tal razón para una empresa es importante tener bien organizada y gestionada la información y documentación, ya que representa su bien intangible más valioso y en la mayoría de los casos hace parte del <i>know how</i> de la misma.
    
    p(data-aos="fade-down").mb-3.mt-3 En el proceso de diseño y desarrollo de un producto electrónico, cada etapa genera una amplia variedad de documentación. En la etapa de diagramación de la placa de circuito impreso, por ejemplo, se pueden obtener archivos esquemáticos, listas de materiales y archivos de fabricación, entre otros. Por otro lado, en la etapa de modelamiento mecánico, se pueden generar planos mecánicos y estructurales, así como archivos de fabricación mecánica, entre otros. En resumen, cada etapa del proceso de desarrollo de un producto electrónico implica la producción de documentación específica y valiosa, que debe ser gestionada y organizada adecuadamente para su uso posterior en la fabricación, pruebas y mantenimiento del producto final.
    
    p(data-aos="fade-up").mb-5.mt-3 A continuación, se pueden observar diferentes tipos de documentos presentes en el desarrollo de un producto electrónico.
    
    .tarjeta.tarjeta-gris.p-4.mb-5(data-aos="fade-right")
      SlyderC.mb-3(:datos="datosSlyder")


    //- .tarjeta.tarjeta-gris.p-4.mb-5(data-aos="fade-right") 
    //-   SlyderA(tipo="b")
    //-     .row.justify-content-center.align-items-center.mt-3
    //-       .col-lg-4.mb-4.mb-md-0.my-3
    //-         h4 Plano mecánico
    //-       .row.justify-content-center.mt-3
    //-         .col-lg-8.my-3
    //-           img.img-a.img-t(src='@/assets/curso/intro/img3.svg', alt='')      
    //-     .row.justify-content-center.mt-3
    //-       .col-lg-4.mb-4.mb-md-0.my-3
    //-         h4 Órden de trabajo
    //-       .col-lg-7.my-3
    //-         img.img-a.img-t(src='@/assets/curso/intro/img4.svg', alt='') 
    //-     .row.justify-content-center.mt-3
    //-       .col-lg-4.mb-4.mb-md-0.my-3
    //-         h4 Encuestas
    //-       .col-lg-7.my-3
    //-         img.img-a.img-t(src='@/assets/curso/intro/img5.svg', alt='')      
    //-     .row.justify-content-center.mt-3
    //-       .col-lg-4.mb-4.mb-md-0.my-3
    //-         h4 Lista de materiales
    //-       .col-lg-7.my-3
    //-         img.img-a.img-t(src='@/assets/curso/intro/img6.svg', alt='')  
    //-     .row.justify-content-center.mt-3
    //-       .col-lg-4.mb-4.mb-md-0.my-3
    //-         h4 Plano esquemático  
    //-       .col-lg-7.my-3
    //-         img.img-a.img-t(src='@/assets/curso/intro/img7.svg', alt='')      
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
    datosSlyder: [
      {
        titulo: 'Plano mecánico',
        imagen: require('@/assets/curso/intro/img3.svg'),
      },
      {
        titulo: 'Órden de trabajo',
        imagen: require('@/assets/curso/intro/img4.svg'),
      },
      {
        titulo: 'Encuestas',
        imagen: require('@/assets/curso/intro/img5.svg'),
      },
      {
        titulo: 'Lista de materiales',
        imagen: require('@/assets/curso/intro/img6.svg'),
      },
      {
        titulo: 'Plano esquemático',
        imagen: require('@/assets/curso/intro/img7.svg'),
      },
    ],
  }),
}
</script>

<style lang="sass"></style>
