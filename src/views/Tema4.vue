<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Metodologías de ajustes

    .row.justify-content-center.align-items-center.mb-3
      .col-lg-5
        figure
         img(src="@/assets/curso/temas/tema4/img1.png", alt="alt")
      .col-lg-7
        .row.crd.p-4.mb-4.cajon-tema1.color-acento-contenido
          p.mb-0.text-small A nivel general, las tarjetas de circuito impreso como producto final, requieren actividades de verificación, valoración y pruebas de funcionalidad de cada uno de sus componentes y subsistemas, que garanticen la calidad y el correcto funcionamiento, conforme a los parámetros establecidos desde su diseño; como por ejemplo, la seguridad eléctrica, riesgos ante daños mecánicos, físicos, en caso de incendio, compatibilidad electromagnética y todos los factores que influyen en el mismo y la construcción de productos electrónicos. Dichas actividades, permiten, además, evaluar las alternativas de diseño utilizadas, de tal manera que se optimicen los procesos.
        .cajon
          .row.justify-content-around.align-items-center
            .col-sm-2
              img(src="@/assets/curso/temas/tema4/img2.svg")
            .col-sm-10
              p.mb-0.text-small(data-aos="fade-up") Una vez se hayan realizado los ajustes al concepto inicial del producto a través del análisis, la verificación y validación, se definen las especificaciones finales del producto a desarrollar y se inicia con las demás actividades, que forman parte de la maduración del concepto en el desarrollo de un producto electrónico.
      
      .col-12.titulo-sexto.color-acento-contenido.mt-5.offset-lg-2
        p.titulo.pb-0.mb-0 <b>Tabla 1.</b> Formato modelo de evaluación cuantitativa
      .tabla-c.color-primario(data-aos="fade-down")
      
        table
          thead.color-head-table
            tr
              th 1. Estado de desarrollo
              th Calificación de 1 a 9
              th Observaciones

          tbody
            tr
              td En este ejercicio, la idea es poder asignar un valor, de acuerdo con el estado de desarrollo, por ejemplo, si el prototipo está un TRL1, la calificación será de 1, o si, por el contrario, se cuenta con un prototipo en TRL 9, la calificación será de 9.
              td 
              td 
            tr
              td TRL 1 Observaciones de los principios básicos.
              td 
              td 
            tr
              td CTRL 2 Formulación del concepto
              td
              td
            tr 
              td TRL 3 Prueba experimental del concepto
              td
              td
            tr
              td TRL 4 Validación del desarrollo en entorno laboratorio
              td
              td
            tr 
              td TRL 5 Validación del desarrollo en entorno pertinente
              td
              td
            tr
              td TRL 6 Demostración del desarrollo en entorno pertinente
              td
              td
            tr 
              td TRL 7 Demostración del desarrollo en entorno real
              td
              td
            tr
              td TRL 8 Desarrollo completo y certificado
              td
              td
          thead.color-head-table
            tr
              th 2. Mercado y aplicación
              th Calificación de 1 a 5
              th Observaciones  
            tbody
            tr
              td Sectores de aplicación
              td 
              td 
            tr
              td Margen del principal sector
              td 
              td 
            tr
              td Tamaño mercado principal sector
              td
              td
            tr 
              td Costo inversión paso a siguiente fase
              td
              td
            tr
              td Puntaje mercado y aplicación
              td
              td
          thead.color-head-table
            tr
              th 3. Perfil equipo investigador
              th Calificación de 1 a 5
              th Observaciones  
            tbody
            tr
              td Interés del inventor
              td 
              td 
            tr
              td Vínculo con empresas
              td 
              td 
            tr
              td Disponibilidad inventor
              td
              td
            tr 
              td Dependencia de un investigador
              td
              td
            tr
              td Puntaje perfil equipo investigador
              td
              td
          thead.color-head-table
            tr
              th 4. Estado de la técnica - grado de novedad
              th Calificación de 1 a 5
              th Observaciones  
            tbody
            tr
              td Posibles afectaciones del prototipo innovador en patentes o mercado
              td 
              td 
            tr
              td Posibles afectaciones del prototipo innovador en artículos
              td 
              td 
            tr
              td Trayectoria de la investigación
              td
              td
            tr 
              td Tecnologías sustitutas
              td
              td
            tr
              td Puntaje estado de la técnica
              td
              td
          thead.color-head-table
            tr
              th 5. Barreras de entrada
              th Calificación de 1 a 5
              th Observaciones  
            tbody
            tr
              td Impacto medio ambiente
              td 
              td 
            tr
              td Normatividad aplicable
              td 
              td 
            tr
              td Alineación con política regional
              td
              td
            tr 
              td Alineación con política universitaria
              td
              td
            tr
              td Barreras de entrada
              td
              td
      figcaption Nota. Adaptada de de Sarraipa, J., Artífcie, A, Jiménez, H. (2019). 
    p(data-aos="fade-right").mb-3 Cuando se diseña un prototipo electrónico, no solo se debe tener en cuenta su funcionamiento en condiciones normales, sino también se deben tener en cuenta todos los factores que permitan proteger el producto contra cualquier falla por condiciones externas.
    p(data-aos="fade-left").mb-3 Según la IEC 60204-1, Capítulo 7, los efectos dañinos que pueden presentarse en un producto electrónico son los siguientes, ver figura 10.
    
    .row.mb-3.mt-3
      .titulo-sexto.color-acento-contenido.mb-3.offset-lg-2(data-aos="fade-left")
        p.titulo.pb-0.mb-0 <b>Figura 10.</b> <i>Efectos dañinos</i>
        
    .row.justify-content-center.mb-3
      .col-lg-4
        figure(data-aos="zoom-in")
          img(src="@/assets/curso/temas/tema4/img7.svg", alt="alt").img400.m-auto
      .col-lg-8.mt-5

        SlyderF.custom.mb-5(columnas="col-lg-6 col-xl-4").mt-5
          .tarjeta-slyder-custom.color-primario.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src="@/assets/curso/temas/tema4/img8.svg", alt="alt").img100.m-auto
            p.text-center.mb-0 Sobrecorriente derivada de un cortocircuito o motor sobrecargado

          .tarjeta-slyder-custom.color-primario.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src="@/assets/curso/temas/tema4/img9.svg", alt="alt").img100.m-auto
            p.text-center.mb-0 Pérdida de enfriamiento de motores

          .tarjeta-slyder-custom.color-primario.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src="@/assets/curso/temas/tema4/img10.svg", alt="alt").img100.m-auto
            p.text-center.mb-0 Cambios de temperatura

          .tarjeta-slyder-custom.color-primario.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src="@/assets/curso/temas/tema4/img11.svg", alt="alt").img100.m-auto
            p.text-center.mb-0 Pérdida o reducción del voltaje de alimentación

          .tarjeta-slyder-custom.color-primario.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src="@/assets/curso/temas/tema4/img12.svg", alt="alt").img100.m-auto
            p.text-center.mb-0 Sobrevelocidad de los equipos o elementos del equipo
          
          .tarjeta-slyder-custom.color-primario.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src="@/assets/curso/temas/tema4/img13.svg", alt="alt").img100.m-auto
            p.text-center.mb-0 Falla de la conexión a tierra o corriente residual

          .tarjeta-slyder-custom.color-primario.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src="@/assets/curso/temas/tema4/img14.svg", alt="alt").img100.m-auto
            p.text-center.mb-0 Conexión incorrecta de las fases eléctricas

          .tarjeta-slyder-custom.color-primario.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src="@/assets/curso/temas/tema4/img15.svg", alt="alt").img100.m-auto
            p.text-center.mb-0 Sobretensiones debidas a rayos y conmutaciones
   
    p(data-aos="fade-right").mb-3 Para realizar una valoración cualitativa se puede evaluar y analizar la tecnología y sus resultados de un modo general; o de un modo más específico, como ejemplo se puede citar el modelo que presenta el libro “Metodología de evaluación de prototipo innovador” el cual se puede observar en la figura 11.
    
    .row.mb-3.mt-3
      .titulo-sexto.color-acento-contenido.mb-3.offset-lg-2(data-aos="fade-left")
        p.titulo.pb-0.mb-0 <b>Figura 11.</b> <i>Metodología de evaluación de un producto innovador</i>
        
      .row.justify-content-center.align-items-center 
        .col-lg-8
          figure
            img(src='@/assets/curso/temas/tema4/img4.svg', alt='Metodología de evaluación de un producto innovador')
            figcaption Adaptado de Sarraipa, J., Artífcie, A, Jiménez, H. (2019).

    .row.justify-content-center.align-items-center.mt-5
      .col-6
            p Este es un método empleado por la Nasa desde 1986, en el cual sobresalen 3 factores:
            ul.lista-ul--color.ps-3
              li
                i.fas.fa-angle-right.txt
                | Definir 10 criterios de evaluación basados en el resultado esperado; es decir, teniendo en cuenta cuales son los objetivos del desarrollo de dicho producto.
              li
                i.fas.fa-angle-right.txt
                | Identificar las posibles alternativas de diseño, de tal manera que con ellas se busquen todas las perspectivas que describen el proceso de principio a fin y así se pueda garantizar que los resultados, en cualquiera de los casos sean los esperados; es decir, este proceso, generará confianza en el hacer. 
              li
                i.fas.fa-angle-right.txt
                | Evaluar las alternativas.
            p En este proceso se hace necesaria la participación de varios expertos, que realizarán su apreciación individual de cada uno de los criterios, dados por los objetivos de diseño; con el fin de señalar un consenso que permita definir mejor la ruta de diseño, implementación y obtención de resultados.
          
      .col-4(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/tema4/img5.png", alt="alt", style="width:450px;").m-auto
    p(data-aos="fade-right").mb-3.mt-5 Otro método cualitativo de valoración de un prototipo electrónico, de acuerdo con Sarraipa, J., Artífcie, A, Jiménez, H. (2019), es el creado en el Tamarack Institute en Canadá en el año 2019; el cual consta de cinco pasos importantes, ver figura 12.
    
    .row.mb-3.mt-3.justify-content-center.align-items-center
      .titulo-sexto.color-acento-contenido.mb-3.offset-lg-2(data-aos="fade-left")
        p.titulo.pb-0.mb-0 <b>Figura 12.</b> <i>Método cualitativo de Tamarack Institute Canadá</i>

      figure
        img(src='@/assets/curso/temas/tema4/img6.svg', alt='Método cualitativo de Tamarack Institute Canadá')
    
    
</template>

<script>
export default {
  name: 'Tema4',
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
