<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Cesación del consumo del tabaco y atención del tabaquismo
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 33130186
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 48
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración: 
                p.banner-principal__datos__item__texto 1(un) mes
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual
              
                    

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/E5VqqUVLYCE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p Este programa surge de la gestión de la mesa sectorial de “salud” en relación con otras instancias, como el Ministerio de Salud y Protección Social, con el propósito de controlar el consumo de tabaco a través de estrategias de intervención y promoción de la cesación del consumo y dar tratamiento al paciente fumador desde lo físico y el acompañamiento emocional.

    p El SENA ofrece este programa que incluye las temáticas de la normatividad, el rol de los profesionales de la salud en el control de tabaco, la carga de enfermedad en Colombia e influencia del tabaquismo en la infección por coronavirus, entre otros.

    p Buscando cumplir con el marco político y normativo del Ministerio de Salud y Protección Social frente al control del consumo de tabaco en el país, esta formación estará dirigida al personal de la salud como auxiliares, técnicos y/o profesionales para ayudar en la implementación de las directrices nacionales para el control del tabaco y redundará en la disminución de la carga de enfermedad por un factor de riesgo que puede prevenirse. 


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p De acuerdo con la Organización Mundial de la Salud – OMS (2011), aproximadamente 6 millones de personas mueren al año por enfermedades asociadas al consumo, y más de 600.000 personas no fumadoras están expuestas a humo de tabaco. Las muertes atribuidas a este factor se relacionan, principalmente, con el cáncer, las enfermedades respiratorias, las enfermedades cardiovasculares, el deterioro de la salud mental global y el incremento en el uso de otras drogas, entre otras. El consumo de tabaco está creciendo en forma constante, sobre todo entre la población adolescente; y en Colombia, la carga de enfermedad atribuible al tabaquismo ocasiona alrededor de 34.800 muertes al año y el sistema de salud invierte alrededor de 6,5 billones de pesos anualmente para atender a las personas con enfermedades provocadas por el consumo o exposición al tabaco.

    p Esta situación llevó a que el Ministerio de Salud y Protección Social estableciera el marco político y normativo para el control del consumo de tabaco en el país y dentro de las estrategias de intervención recomendadas, se encuentra el promover la cesación del consumo y dar tratamiento al paciente fumador mediante la aplicación de intervenciones costo-efectivas y de basada evidencia científica que están cubiertas por el sistema de salud colombiano. A pesar de ello, más del 50% de los prestadores de atención primaria y los profesionales de la salud, no ofrecen estas intervenciones de manera sistemática debido a la falta de conocimiento acerca del tabaquismo y su tratamiento, que constituye uno de los principales obstáculos para ofrecer ayuda a los consumidores de tabaco.

    p En consecuencia, el desarrollar capacidades en el personal de salud y los prestadores de servicios de salud del país ayudará en la implementación de las directrices nacionales para el control del tabaco y redundará en la disminución de la carga de enfermedad por un factor de riesgo que es totalmente prevenible.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a <br>desarrollar

    p Controlar riesgo bucal según normativa de salud oral.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de <br>ingreso

    p El programa Cesación del consumo del tabaco y atención del tabaquismo, está dirigido a: personal de salud, auxiliares, técnicos, profesionales del sector salud.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil de <br>egreso

    p El egresado estará en capacidad de reconocer las directrices para el desarrollo de programas de cesación del consumo del tabaco y atención del tabaquismo, teniendo en cuenta el marco normativo nacional e internacional y el rol del personal de la salud; así como realizar la consejería breve para la cesación del consumo de tabaco y atención del tabaquismo a partir de la valoración.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 6. Estrategia <br>metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en el utilización de las tecnologías de la información y la comunicación, integradas en ambientes virtuales de aprendizaje que, en todo caso, recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 

    p Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el que hacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:

    ul.lista-ul
      li.mb-0
        i.lista-ul__vineta
        p  El instructor – Tutor.
      li.mb-0
        i.lista-ul__vineta
        p El entorno.
      li.mb-0
        i.lista-ul__vineta
        p las TIC.
      li.mb-0
        i.lista-ul__vineta
        p El trabajo colaborativo.



  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
