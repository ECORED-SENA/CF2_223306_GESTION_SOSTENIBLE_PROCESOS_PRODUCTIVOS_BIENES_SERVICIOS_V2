<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="zoom-in-left")
      .titulo-principal__numero
        span 4
      h1 Toma de decisiones e indicadores de verificación

    .row.justify-content-center.align-items-center.mb-5           
      .col-lg-6
        .color-fondo-text1.bg-color.mb-3(data-aos="fade-down")
          .color-fondo-text1__texto 
            p Es un método en el que se reúne la información o los datos que la organización está desarrollando en su planeación estratégica, con el objetivo de evaluar diferentes alternativas para llegar a tomar la mejor decisión final posible. #[b Ello implica que las diferentes partes interesadas involucradas en los procesos analicen la información recopilada y diseñen las mejores estrategias para tomar una decisión final.]

        p(data-aos="fade-down").mb-0 Por otro lado, el proceso de toma de decisiones debe enfrentarse a ciertos pasos para resolver una situación, así: 
      .col-lg-4
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img112.png', alt='')

    .bg22
      .pt-5
        .row.justify-content-center.align-items-center.mb-5           
          .col-lg-8   
            PasosA.color-acento-contenido(tipo="n")
              .row.justify-content-center.align-items-center
                .col-lg-10
                  h4(data-aos="fade-left") Definir el problema
                  p(data-aos="fade-left") Primero debe definir el problema en el que debe analizar la situación a la que se está enfrentado.
                .col-lg-2
                  img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img113.png', alt='')
              .row.justify-content-center.align-items-center
                .col-lg-2.order-1
                  img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img114.png', alt='')            
                .col-lg-10.text-start.order-lg-2
                  h4(data-aos="fade-right") Alternativas
                  p(data-aos="fade-right") Luego, identificar las diferentes alternativas posibles para optar por las acciones que se pueden desarrollar.
              .row.justify-content-center.align-items-center
                .col-lg-10
                  h4(data-aos="fade-left") Resultados
                  p(data-aos="fade-left") Entonces, revisar los posibles resultados que se pueden generar con las alternativas propuestas.
                .col-lg-2
                  img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img115.png', alt='')
              .row.justify-content-center.align-items-center
                .col-lg-2.order-1
                  img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img116.png', alt='')            
                .col-lg-10.text-start.order-lg-2
                  h4(data-aos="fade-right") Control
                  p(data-aos="fade-right") Es así como se optará por la mejor alternativa, controlando los resultados de acuerdo con la opción elegida y evaluar los resultados obtenidos con base en la decisión tomada, revisando las ventajas y desventajas.

    p(data-aos="fade-down").mb-5 El proceso de toma de decisiones presenta las siguientes características que se deben tener presentes: 

    .titulo-sexto.color-acento-contenido(data-aos='fade-right')
      h5 Tabla 4
      span Toma de decisiones
    .tabla-a.tpurple.mb-5(data-aos='fade-left')
      table.table1         
        thead
          tr
            th Título
            th Objetivo y función
        tbody
          tr
            td.text-bold.px-5 Racional
            td Se revisan las diferentes fuentes o información recopilada, con el objetivo de analizar las diferentes alternativas de forma racional. 
          tr
            td.text-bold.px-5 Intuitivo 
            td El individuo tiene presente su experiencia personal y su intuición para tomar alguna de las alternativas propuestas.
          tr
            td.text-bold.px-5 Personal 
            td De forma privada el individuo toma una decisión.
          tr
            td.text-bold.px-5 De rutina 
            td Es el proceso que un individuo o grupo desarrolla a diario frente a situaciones que no son temas complejos.
          tr
            td.text-bold.px-5 De emergencia
            td Es el proceso que toma un individuo o grupo frente a una situación nueva y excepcional.
          tr
            td.text-bold.px-5 De grupo 
            td Es el proceso que se realiza entre los grupos del equipo de trabajo de la organización en el que se llega en consenso a la toma de alternativas de decisión. 
          tr
            td.text-bold.px-5 Individual 
            td Proceso que desarrolla una persona en una organización de manera autónoma.
          tr
            td.text-bold.px-5 Organizacional 
            td Proceso que realizan uno o varios individuos miembros de una organización para tomar una decisión que repercute en el futuro de la institución.  
    Separador 
    #t_4_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 4.1 Herramientas y métodos para la toma de decisiones 

    .row.justify-content-between.align-items-center.position-relative
      .col-lg-11.up
        p(data-aos="fade-down") En la toma de decisiones, luego de tener toda la información necesaria para poder analizar y elegir la mejor decisión, existen varias herramientas que permiten hacer un análisis profundo de la información, con lo cual se lleva a cabo la toma de decisión más fácil y segura. 

        h5(data-aos="fade-down") Algunas de las herramientas más destacadas y de uso actual para la toma de decisiones en las organizaciones y proyectos son:    
      .col-lg-1.col-5.mb-lg-0.mb-3.d-none.d-lg-block 
        .imagen-absolute8.pb-5
          img(data-aos="zoom-in")(src='@/assets/curso/temas/img117.svg', alt='')

    AcordionA.my-5(tipo="a" clase-tarjeta="tarjeta bg27")(data-aos="fade-right")
      .row.justify-content-center.align-items-start(titulo="Análisis FODA")
        .col-lg-7
          p En este análisis se busca identificar fortalezas, oportunidades, debilidades y amenazas de la empresa. Esta herramienta busca analizar de manera profunda cada uno de los factores de la empresa, permitiendo así una toma de decisión más certera. 
        .col-lg-5
          img.img-a.img-t(src='@/assets/curso/temas/img118.png', alt='Esquema de la matriz DOFA: debilidades, oportunidades, fortalezas y amenazas.')   
      .row.justify-content-center.align-items-start(titulo="Matriz de decisión")
        .col-lg-7
          p Es una herramienta gráfica que permite tomar una decisión radical, evaluando y escogiendo la mejor opción entre diferentes alternativas, teniendo en cuenta los factores de cada alternativa para la decisión final. 
        .col-lg-5
          img.img-a.img-t(src='@/assets/curso/temas/img119.png', alt='Ejemplo de esquema de una matriz de decisión en la que se analizan una serie de ideas con base en un listado de criterios.')
      .row.justify-content-center.align-items-start(titulo="Árbol de decisión")
        .col-lg-7
          p Es el diseño de un mapa donde se muestran ciertos resultados de las posibles decisiones que se pueden tomar, permitiendo comparar entre varias acciones, sus probabilidades y beneficios. 
        .col-lg-5
          img.img-a.img-t(src='@/assets/curso/temas/img120.png', alt='Ejemplo de un esquema de árbol de decisión en el que se muestran como distintos elementos van ramificándose de acuerdo a sus resultados.')
      .row.justify-content-center.align-items-start(titulo="Análisis de Pareto")
        .col-lg-7
          p Es un diagrama que permite evaluar el nivel de prioridad que se le debe dar a las acciones a tomar, para llegar al objetivo final. Se trata de una técnica que clasifica de mayor a menor importancia la información. Lo hace de manera gráfica para favorecer una fácil comprensión. 
        .col-lg-5
          img.img-a.img-t(src='@/assets/curso/temas/img121.png', alt='Ejemplo de un análisis de Pareto a través de una representación gráfica de barras.')
      .row.justify-content-center.align-items-start(titulo="<i>Workflows</i>")
        .col-lg-7
          p Se trata de un conjunto de ideas organizadas en forma de flujo de diagrama; las mismas están enfocadas hacia el objetivo principal, llevando cada día, un orden que permita construir el camino a desarrollar y se haga seguimiento a la información obtenida para la creación de nuevas tareas. 
        .col-lg-5
          img.img-a.img-t(src='@/assets/curso/temas/img122.png', alt='Ejemplo de representación de un diagrama de trabajo en el que se evidencie el camino a seguir.')
      .row.justify-content-center.align-items-start(titulo="Indicadores")
        .col-lg-7
          p Un indicador es aquel que permite dar un veredicto final, permitiendo juzgar los resultados que se han obtenido sobre los objetivos desarrollados en el proyecto, detallando y midiendo los logros de cada uno de los objetivos. Los indicadores pueden ser cualitativos y cuantitativos. 
        .col-lg-5
          img.img-a.img-t(src='@/assets/curso/temas/img123.png', alt='Ejemplo de un gráfico de barras representando una serie de indicadores.')

    p(data-aos="fade-down").mb-5 La siguiente tabla muestra cuatro formas específicas para la creación de indicadores. 
    .titulo-sexto.color-acento-contenido(data-aos='fade-right')
      h5 Tabla 5
      span Cuatro maneras para crear indicadores
    .tabla-a.tpurple.mb-5(data-aos='fade-left')
      table.table1         
        thead
          tr
            th Título
            th Objetivo y función
           
        tbody
          tr
            td.text-bold.px-5 Indicador cuantitativo
            td Significa medir o contar. Suministra números exactos, por ejemplo, la cantidad es contada: 20 pares de zapatos; el 100% de alumnos matriculados. 
          tr
            td.text-bold.px-5 Indicador cualitativo
            td Significa escalar o graduar. Suministra una descripción gradual, por ejemplo, la calidad de la mercadería puede ser graduada como muy buena - buena - promedio - mala - muy mala. 
          tr
            td.text-bold.px-5 Indicador no graduable 
            td Significa clasificar. Informa sobre categorías no graduables, por ejemplo, hay sal disponible: sí/no, quién toma las decisiones finales en la tienda: mujer/hombre.
          tr
            td.text-bold.px-5 Indicador descriptivo 
            td Describe cualitativamente en palabras, por ejemplo, ¿cómo está siendo administrada la tienda? La respuesta describe en palabras uno o más aspectos. La descripción puede tener una determinada estructura (aspectos positivos - negativo; liderazgo - compras - ventas - contabilidad).


    .bg15.px-5.mb-3.py-3
      .row.justify-content-center.align-items-center.ps-5.mov           
        .col-lg-6.my-3
          h5(data-aos="fade-down").mb-4 Existen varios tipos de indicadores, entre los cuales se encuentran:
          .row.justify-content-center.align-items-center.ps-5           
            .col-lg-6.my-3        
              ul.lista-ul--color(data-aos="fade-down")
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Indicador de productividad.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Indicador de eficiencia.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Indicador de eficacia.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Indicador de efectividad.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Indicador de calidad. 
            .col-lg-6.my-3        
              ul.lista-ul--color(data-aos="fade-down")
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Indicador de capacidad.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Indicador de ganancia.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Indicador de rentabilidad.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Indicador de valor. 
        .col-lg-6 
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img124.png', alt='') 

    .row.justify-content-center.align-items-center.my-5           
      .col-lg-12.pt-5
        .tarjeta.position-relative.rounded-0.bg1.p-4.mb-5(data-aos="flip-down")
          .row.justify-content-center.align-items-center
            .col-lg-2.col-5.mb-lg-0.mb-3
              .imagen-absolute9
                img(data-aos="zoom-in")(src='@/assets/curso/temas/img3.svg', alt='')
            .col-lg-10
              p(data-aos="fade-down").mb-0.p-3.text-white #[b ¡Importante!] Los indicadores deben contar con ciertas características, como: validez, precisión, medición, oportunidad, programación. 

    .row.justify-content-center.align-items-stretch.my-5 
      .col-lg-4.bg9.p-0.rad-top-right.imgmov
        .imgs-flotantes2.up
          img.img-flotante2.d-lg-block.d-none(data-aos="zoom-in")(src='@/assets/curso/temas/img127.png', alt='Imagen decorativa')      
        img.img-t.w-100(data-aos="zoom-in")(src='@/assets/curso/temas/img126.png', alt='')           
      .col-lg-6.bg9.p-3.ps-4
        img.img-t.mb-3(data-aos="zoom-in")(src='@/assets/curso/temas/img125.png', alt='')
        p(data-aos="fade-down").mb-0 Los indicadores de calidad son usados, comúnmente, para monitorear las actividades del programa. Entre más definido se encuentre el indicador, habrá menos errores y confusión para analizar la información. En ocasiones, los indicadores se ven limitados por la falta de disponibilidad de datos, es por eso que la información debe ser completa y coherente.

    Separador 
    #t_4_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 4.2 Técnicas de análisis de la información 
    .row.justify-content-between.align-items-center.position-relative.mb-5
      .col-lg-1.col-5.mb-lg-0.mb-3.d-none.d-lg-block 
        .imagen-absolute10
          img(data-aos="zoom-in")(src='@/assets/curso/temas/img128.png', alt='')      
      .col-lg-11.up
        p(data-aos="fade-down") Son un conjunto de datos que se recolectan para lograr la conclusión de cierta información en favor de la toma de la decisión. Esta información es estudiada a fondo para dar una conclusión a su resultado. En esta acción suele usarse un programa estadístico que favorezca el análisis de variables y relaciones multivalentes.         

    .bg12.px-5.mb-3.py-3
      .row.justify-content-center.align-items-center.ps-5.mov
        h5(data-aos="fade-down").mb-4 Existen técnicas de análisis de información simples, como lo son los análisis de imagen, video y voz, pero también existen técnicas más complejas como:
        .col-lg-6.my-3
          .row.justify-content-center.align-items-start.ps-5           
            .col-lg-6.my-3        
              ul.lista-ul--color(data-aos="fade-down")
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Análisis de correlaciones.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Análisis de regresión.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Visualización de datos.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Análisis de escenarios.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 <i>Data mining</i>.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Análisis de sentimientos.
            .col-lg-6.my-3        
              ul.lista-ul--color(data-aos="fade-down")
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Análisis semántico de textos.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Análisis de patentes y literatura científica.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Simulación de Monte Carlo.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Programación y optimización matemática.
                li.d-flex 
                  i.fas.fa-atom
                  p.mb-0 Predicción matemática.
        .col-lg-6 
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img129.png', alt='') 

    .row.justify-content-center.align-items-center      
      .col-lg-12.pt-5
        .tarjeta.position-relative.rounded-0.bg3.p-4.mb-5(data-aos="flip-down")
          .row.justify-content-center.align-items-center
            .col-lg-2.col-5.mb-lg-0.mb-3
              .imagen-absolute11
                img(data-aos="zoom-in")(src='@/assets/curso/temas/img3.svg', alt='')
            .col-lg-10
              p(data-aos="fade-down").mb-0.p-3 #[b ¡Atención!] Las técnicas de análisis dependen de la información que se tenga, por tanto, su recolección se debe realizar mediante mecanismos como observación, entrevistas, encuestas y otras estrategias básicas, todas ellas necesarias para tal fin de recopilarla. Una información recolectada y expresada gráficamente facilita su comprensión y su análisis. La misma se clasifica en explicativa y descriptiva.

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
