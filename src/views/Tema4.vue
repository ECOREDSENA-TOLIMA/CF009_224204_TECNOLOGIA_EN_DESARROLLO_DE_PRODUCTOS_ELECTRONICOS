<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Metodologías de ajustes

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6
        figure
         img(src="@/assets/curso/temas/tema4/img1.svg", alt="alt")
      .col-lg-6
        .row.crd.p-4.mb-4.cajon-tema1.color-acento-contenido
          p.mb-0 A nivel general, las tarjetas de circuito impreso como producto final, requieren actividades de verificación, valoración y pruebas de funcionalidad de cada uno de sus componentes y subsistemas, que garanticen la calidad y el correcto funcionamiento, conforme a los parámetros establecidos desde su diseño; como por ejemplo, la seguridad eléctrica, riesgos ante daños mecánicos, físicos, en caso de incendio, compatibilidad electromagnética y todos los factores que influyen en el mismo y la construcción de productos electrónicos. Dichas actividades, permiten, además, evaluar las alternativas de diseño utilizadas, de tal manera que se optimicen los procesos.
        .cajon
          .row.justify-content-around.align-items-center
            .col-sm-2
              img(src="@/assets/curso/temas/tema4/img2.svg")
            .col-sm-10
              p(data-aos="fade-up") Una vez se hayan realizado los ajustes al concepto inicial del producto a través del análisis, la verificación y validación, se definen las especificaciones finales del producto a desarrollar y se inicia con las demás actividades, que forman parte de la maduración del concepto en el desarrollo de un producto electrónico.
      
      .col-12.titulo-sexto.color-acento-contenido.mt-5
        p.titulo.pb-0.mb-0 <b>Tabla 1.</b> Formato modelo de evaluación cuantitativa
      .tabla-c.color-primario(data-aos="fade-down")
      
        table
          caption Nota. Adaptada de de Sarraipa, J., Artífcie, A, Jiménez, H. (2019).
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
              td Puntaje Mercado y Aplicación
              td
              td
          thead.color-head-table
            tr
              th 3. Perfil equipo investigador
              th Calificación de 1 a 5
              th Observaciones  
            tbody
            tr
              td Interés del Inventor
              td 
              td 
            tr
              td Vínculo con empresas
              td 
              td 
            tr
              td Disponibilidad Inventor
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
              td Puntaje Estado de la técnica
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
    p(data-aos="fade-right").mb-3 Cuando se diseña un prototipo electrónico, no solo se debe tener en cuenta su funcionamiento en condiciones normales, sino también se deben tener en cuenta todos los factores que permitan proteger el producto contra cualquier falla por condiciones externas.
    p(data-aos="fade-left").mb-5 Según la IEC 60204-1, Capítulo 7, los efectos dañinos que pueden presentarse en un producto electrónico son los siguientes, ver figura 4.
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5

      SlyderF(columnas="col-lg-6 col-xl-4")
        .tarjeta.color-acento-botones.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema4/img3.svg' alt='AvatarTop')
          h2.text-center FIRST
          p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

        .tarjeta.color-acento-botones.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema4/img3.svg' alt='AvatarTop')
          h2.text-center 2
          p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

        .tarjeta.color-acento-botones.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema4/img3.svg' alt='AvatarTop')
          h2.text-center 3
          p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

        .tarjeta.color-acento-botones.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema4/img3.svg' alt='AvatarTop')
          h2.text-center 4
          p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

        .tarjeta.color-acento-botones.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema4/img3.svg' alt='AvatarTop')
          h2.text-center 5
          p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

        .tarjeta.color-acento-botones.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema4/img3.svg' alt='AvatarTop')
          h2.text-center 6
          p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

        .tarjeta.color-acento-botones.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema4/img3.svg' alt='AvatarTop')
          h2.text-center 7
          p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

        .tarjeta.color-acento-botones.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/temas/tema4/img3.svg' alt='AvatarTop')
          h2.text-center LAST
          p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.
    
    p(data-aos="fade-right").mb-3 Para realizar una valoración cualitativa se puede evaluar y analizar la tecnología y sus resultados de un modo general; o de un modo más específico, como ejemplo se puede citar el modelo que presenta el libro “Metodología de evaluación de prototipo innovador” el cual se puede observar en la figura 5.
    .row.justify-content-center.align-items-center
      .col-lg-8(data-aos="fade-up")
        .titulo-sexto.color-acento-contenido.mb-3
          h5  Figura 5 Metodología de evaluación de un producto innovador
        figure
          img(src='@/assets/curso/temas/tema4/img4.png', alt='Metodología de evaluación de un producto innovador')
          figcaption Adaptado de Sarraipa, J., Artífcie, A, Jiménez, H. (2019).

    .row.justify-content-center.mt-5
      .col-7
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
          
      .col-3(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/tema4/img5.svg", alt="alt", style="width:450px;").m-auto
    p(data-aos="fade-right").mb-3.mt-5 Otro método cualitativo de valoración de un prototipo electrónico, de acuerdo con Sarraipa, J., Artífcie, A, Jiménez, H. (2019), es el creado en el Tamarack Institute en Canadá en el año 2019; el cual consta de cinco pasos importantes, ver figura 6.
    .row.justify-content-center.align-items-center
      .col-lg-12(data-aos="zoom-out")
        .titulo-sexto.color-acento-contenido.mb-3
          h5   Figura 6 Método cualitativo de Tamarack Institute Canadá
        figure
          img(src='@/assets/curso/temas/tema4/img6.png', alt='Método cualitativo de Tamarack Institute Canadá')


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
