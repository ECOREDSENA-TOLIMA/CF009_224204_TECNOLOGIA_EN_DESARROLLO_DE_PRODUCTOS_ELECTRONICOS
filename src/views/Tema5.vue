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
                | Producción de <em>software</em>.
              li
                i.fas.fa-angle-right.txt
                | Producción de productos electrónicos terminados.
            p Para el caso de los diseñadores de productos electrónicos, es importante tener en cuenta la siguiente ficha de <em>marketing</em> propuesta por Sarraipa, J., Artífcie, A, Jiménez, H. (2019), en el documento “metodología de evaluación de prototipo innovador”, ver figura 13.
          
      .col-5(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/tema5/img1.png", alt="alt", style="width:450px;").m-auto
    
    .row.mb-3.mt-3
      .titulo-sexto.color-acento-contenido.mb-3.offset-lg-2(data-aos="fade-left")
        p.titulo.pb-0.mb-0 <b>Figura 13.</b> <i>Ficha de marketing para el desarrollo de un producto tecnológico</i>
    
    .row.justify-content-center.mt-5
      .col-6
        ImagenInfografica.color-acento-botones
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/temas/tema5/img2.svg', alt='Texto que describa la imagen')
              
          .tarjeta-slyder-custom.color-acento-contenido.p-3(x="17.3%" y="12.2%" numero="+")
            .h5.mb-2 Contexto
            p Es necesario redactar el problema u oportunidad que soluciona o aprovecha el prototipo innovador. Se debe plantear un contexto breve y destacar los problemas y dificultades de las principales soluciones que abordan el problema, o en el caso de la oportunidad, la magnitud de la brecha existente. Es necesario dejar claro el tamaño del problema u oportunidad que se quiere explotar. Por ejemplo, se han de definir los ingresos, eficiencia o rendimiento, costos, tasas de enfermedad, etc.

          .tarjeta-slyder-custom.color-acento-contenido.p-3(x="83.4%" y="12.2%" numero="+")
            .h5.mb-2 Descripción
            p En este punto, se debe hacer la presentación del prototipo innovador, usando términos de fácil comprensión, para indicar concretamente lo que tiene o lo que hace que se resuelva el problema identificado. Se deben destacar las pruebas/ comparaciones que validen la superioridad del prototipo innovador con respecto a otras soluciones (que conecten directamente con el problema planteado).

          .tarjeta-slyder-custom.color-acento-contenido.p-3(x="3%" y="65.2%" numero="+")
            .h5.mb-2 Propuesta de valor
            p Es el corazón de la ficha y lo que primero capta la atención del cliente o público objetivo por lo cual su mensaje debe ser contundente. Debe ser una oración clara, concisa y que demuestre la esencia principal del prototipo innovador. La propuesta de valor es el enunciado de los beneficios que pueden esperar los clientes de una innovación. 
          
          .tarjeta-slyder-custom.color-acento-contenido.p-3(x="97.3%" y="65.2%" numero="+")
            .h5.mb-2 Aplicaciones
            p En este punto se deben describir las principales aplicaciones del producto tecnológico o el sector de aplicación donde esta puede ser utilizada. De acuerdo con el tipo de prototipo innovador y su contexto, se puede ser más o menos específico. Por ejemplo, para una enzima desarrollada en laboratorio se podrían identificar diferentes aplicaciones tecnológicas como: 1. Depuración. 2. Síntesis de otras moléculas. 3. Destrucción de radicales libres.
          
          .tarjeta-slyder-custom.color-acento-contenido.p-3(x="50.1%" y="97.3%" numero="+")
            .h5.mb-2 Beneficios
            p Es necesario redactar el problema u oportunidad que soluciona o aprovecha el prototipo innovador, planteando un contexto breve y destacando los problemas/ dificultades de las principales soluciones que aborden el problema o en el caso de la oportunidad, la magnitud de la brecha existente. Es necesario dejar claro el tamaño del problema u oportunidad que se quiere explotar.

    p(data-aos="fade-right").mb-3.mt-3 La miniaturización cada vez más de los sistemas electrónicos debido a su alta escala de integración, y lo complejo que puede resultar el desarrollo de un producto electrónico, ha supuesto que en los procesos de manufactura sea indispensable el uso de herramientas de <em>software</em> y <em>hardware</em> cada vez más robustas y precisas.
    p(data-aos="fade-left").mb-3.mt-3 Por tal razón las herramientas CAD/CAM han evolucionado a tal punto que muchos procesos tradicionales de manufactura de productos electrónicos se hayan automatizado; una tarea que antes hacía un operario de forma manual ahora la realiza con ayuda de un <em>software</em> o una máquina.

    .row.mb-3.mt-3
      .titulo-sexto.color-acento-contenido.mb-3.offset-lg-2(data-aos="fade-left")
        p.titulo.pb-0.mb-0 <b>Figura 14.</b> <i>Reinvención de ocupaciones a través de la tecnología</i>
        
    .row.justify-content-center.align-items-center.py-0.mb-5(data-aos="fade-right")
      .col-lg-12.col-12.bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
        .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema5/img3.svg')})`}"
        )
        .bloque-texto-g__texto.p-4
          p.mb-0 Esto ha permitido la reinvención de las ocupaciones en una empresa, pues ya no se capacita en una técnica manual, por el contrario, se le instruye al personal técnico en el uso y operación de la maquinaria o sistemas robotizados que optimizan la labor dentro del puesto de trabajo.
          
    p(data-aos="fade-right").mb-3.mt-3 Teniendo en cuenta la necesidad de garantizar la propuesta de valor que se describe con el diseño y desarrollo del producto electrónico, se hace necesaria la revisión tecnológica, que permite no sólo la verificación del funcionamiento del prototipo, sino su comportamiento y validación en el mercado; de tal manera, que se hace necesaria la autoverificación constante, con respecto a los demás productos electrónicos similares que puedan existir en el mercado actual.
    
    .row(data-aos="fade-down")
      .col-lg-12
        .cajon.color-primario.p-4
          .row.justify-content-around.align-items-center
            .col-sm-1
              img(src="@/assets/curso/temas/tema5/img4.svg")
            .col-lg-11
              p(data-aos="fade-up").mb-3.p-2 Dicho esto, un producto electrónico siempre llevará al análisis de garantías, funcionamiento y rentabilidad en el mercado.

    p(data-aos="fade-left").mb-3.mt-5 Entre la finalidad que se busca de la vigilancia tecnológica, será necesario evaluar permanentemente entre otros factores los siguientes, ver figura 15:

    .row.mb-3.mt-3
      .titulo-sexto.color-acento-contenido.mb-3.offset-lg-2(data-aos="fade-left")
        p.titulo.pb-0.mb-0 <b>Figura 15.</b> <i>Factores a evaluar</i>
          
    figure
      img(src='@/assets/curso/temas/tema5/img5.svg', alt='Factores a evaluar')

    p(data-aos="fade-left").mb-3.mt-3 La información sobre proveedores tendrá una gran relevancia en la implementación del producto electrónico, ya que es quien garantiza la confianza de un producto electrónico, con materias primas de alta calidad y garantía.
  
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
