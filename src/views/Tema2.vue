<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido(data-aos="zoom-in-left")
        .titulo-principal__numero
          span 2
        h1 Equipos de trabajo
      p(data-aos="fade-down").mb-5 En las promotorías es una variable importante que incide en las decisiones no solo de la marca sino, además, de los inversores o clientes. Todo integrante del equipo, desde el fundador hasta el becario, debe demostrar confianza, capacidad de logros y seguridad para los inversores, los cuales buscan esta cultura de “ambición” y compromiso para elegir a quién favorecer con su tiempo y dinero.
  
      .row.justify-content-center.align-items-center.mb-5           
        .col-lg-10(data-aos="zoom-in")
          .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.position-relative
            .bloque-texto-g__img(
              :style="{'background-image':`url(${require('@/assets/curso/temas/img1.png')})`}"
            )
              .imagen-superior.position-absolute.mv.px-4(style='bottom:0% ; left: 30%; z-index:2'): img(src='@/assets/curso/temas/img43.svg')
            .bloque-texto-g__texto.px-4.py-5
              p.mb-0.pe-5.pmov Cada comercio cuenta con sus propios obstáculos y retos al salir al mercado. Si el equipo está concentrado, motivado, cada uno de los esfuerzos dará buenos resultados. Un buen equipo de trabajo tiene buena comunicación y objetivos claros de lo que se va a hacer cumpliendo con lo que se le pide.
  
      .row.justify-content-center.align-items-center.my-5           
        .col-lg-12.pt-5
          .tarjeta.position-relative.rounded-0.bg1.p-4.mb-5(data-aos="flip-down")
            .row.justify-content-center.align-items-center
              .col-lg-2.col-5.mb-lg-0.mb-3
                .imagen-absolute5
                  img(data-aos="zoom-in")(src='@/assets/curso/temas/img3.svg', alt='')
              .col-lg-10
                p(data-aos="fade-down").mb-0.p-3.text-white #[b ¡Importante!] El equipo de trabajo debe ser unido y estar dirigido por una persona líder que conozca la responsabilidad que tiene en el equipo. Quien asuma el liderazgo lleva la responsabilidad total de la promotoría, incluida la toma de decisiones importantes para el cumplimiento del objetivo final de la promotoría.
                
      Separador 
      #t_2_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
        h2 2.1 Tipos y características
      .row.justify-content-between.align-items-center.position-relative
        .col-lg-11.up
          p(data-aos="fade-down") El personal de expertos asignados a las labores de la promotoría suele poseer una gigantesca inclinación por la publicidad y los negocios, así como por las ciencias económicas y empresariales. No obstante, la mayor parte de las organizaciones no acostumbran a solicitar obligatoriamente un título preeminente para esta tarea. #[b Además de ciertas características con las que debe contar el personal, este puede ser clasificado en perfiles como:]      
        .col-lg-1.col-5.mb-lg-0.mb-3.d-none.d-lg-block 
          .imagen-absolute6
            img(data-aos="zoom-in")(src='@/assets/curso/temas/img44.svg', alt='')
  
      .titulo-sexto.color-acento-contenido(data-aos='fade-right')
        h5 Tabla 2 
        span Perfiles del equipo promotor
      .tabla-a.tpurple.mb-5(data-aos='fade-left')
        table.table1
          caption #[b Nota.] Adaptada del Equipo promotor, Cavero (2019).
          thead
            tr
              th(colspan='2') Perfiles del equipo promotor
              
          tbody
            tr
              td.px-5 CEO
              td #[b Consejero delegado o director ejecutivo.] Se trata del máximo responsable de la gestión y dirección administrativa de la empresa.
            tr
              td.px-5 CFO
              td #[b Director financiero.] Encargado de la planificación económica y financiera de la compañía. Es quien decide la inversión, la financiación y el riesgo con el objetivo de conseguir que aumente el valor de la empresa para sus propietarios. 
            tr
              td.px-5 CIO
              td Responsable de los sistemas de tecnologías de la información de la empresa a nivel de procesos y desde el punto de vista de la planificación. 
            tr
              td.px-5 CTO
              td Responsable técnico del desarrollo y el correcto funcionamiento de los sistemas de información desde el punto de vista de la ejecución. 
            tr
              td.px-5 COO
              td #[b Director de operaciones.] Supervisa cómo está funcionando el sistema de creación y distribución de los productos de la empresa para asegurarse de que todos los sistemas funcionen bien. 
  
      p(data-aos="fade-down").mb-5 Un promotor ha de tener en su perfil capacidades y rasgos que le permitan ser competente para lograr ventas y aportar identidad a la marca, a los productos y al equipo mismo. #[b Ser un gran promotor implica cultivar rasgos como:]
      SlyderF.slyder-100.mb-5(columnas="col-lg-6 col-xl-4")(data-aos="fade-right")   
        .tarjeta-avatar
          img.img-a.img-t.img-w(src='@/assets/curso/temas/img45.svg' alt='AvatarTop')
          div.bg19.p-5.h-100
            p.pt-5.mb-0 Responsabilidad, dinamismo, proactividad, don de gente. 
        .tarjeta-avatar
          img.img-a.img-t.img-w(src='@/assets/curso/temas/img46.svg' alt='AvatarTop')
          div.bg20.p-5.h-100
            p.pt-5.mb-0 Habilidades comunicativas de negociación, capacidad de persuasión.
        .tarjeta-avatar
          img.img-a.img-t.img-w(src='@/assets/curso/temas/img47.svg' alt='AvatarTop')
          div.bg19.p-5.h-100
            p.pt-5.mb-0 Iniciativa, orientación al logro de resultados, habilidades comerciales.
        .tarjeta-avatar
          img.img-a.img-t.img-w(src='@/assets/curso/temas/img48.svg' alt='AvatarTop')
          div.bg20.p-5.h-100
            p.pt-5.mb-0 Promociona productos para el incremento de ventas, promueve servicios y productos de la compañía, trata con clientes o público en general.
        .tarjeta-avatar
          img.img-a.img-t.img-w(src='@/assets/curso/temas/img49.svg' alt='AvatarTop')
          div.bg19.p-5.h-100
            p.pt-5.mb-0 Vende sus productos a personas en sus domicilios, vende productos al por menor al público en general.  
  
      .row.justify-content-center.align-items-center          
        .col-lg-12.pt-5
          .tarjeta.position-relative.rounded-0.bg16.p-4.mb-5(data-aos="flip-down")
            .row.justify-content-center.align-items-center
              .col-lg-2.col-5.mb-lg-0.mb-3
                .imagen-absolute1
                  img(data-aos="zoom-in")(src='@/assets/curso/temas/img39.svg', alt='')
              .col-lg-10
                p(data-aos="fade-down").mb-0.p-3 Los promotores generales deben tener la capacidad de asumir riesgos y saber adaptarse de manera rápida a los cambios que se requieran hacer, con la capacidad de adoptar nuevas decisiones para planificar y dirigir la promotoría de la empresa.
  
      p(data-aos="fade-down").mb-5 Entre las características más destacadas con las que debe contar el equipo de trabajo de la promotoría están: 
  
      .row.justify-content-center.align-items-stretch         
        .col-lg-4.my-4 
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img50.png', alt='')
          .bg21.p-3.pt-5.h
            h4 Adaptar
            p.mb-0 Seguir los cambios.                             
        .col-lg-4.my-4 
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img51.png', alt='')
          .bg21.p-3.pt-5.h
            h4 Liderar
            p.mb-0 Llevar a cabo con propiedad el liderazgo.                             
        .col-lg-4.my-4 
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img52.png', alt='')
          .bg21.p-3.pt-5.h
            h4 Identidad
            p.mb-0 Conocer las políticas de la empresa con la que trabaja.  
  
      .row.justify-content-center.align-items-stretch         
        .col-lg-4.my-4 
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img53.png', alt='')
          .bg21.p-3.pt-5.h
            h4 Jerarquizar
            p.mb-0 Tener un jefe promotor a cargo y valorar cada rol de equipo.                  
        .col-lg-4.my-4 
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img54.png', alt='')
          .bg21.p-3.pt-5.h
            h4 Publicitar y crear
            p.mb-0 Generar contenido audiovisual.
        .col-lg-4.my-4 
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img55.png', alt='')
          .bg21.p-3.pt-5.h
            h4 Controlar
            p.mb-0 Medir resultados.
  
      Separador 
      #t_2_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
        h2 2.2 Técnica de moderación de equipos de trabajo  
  
      .row.justify-content-center.align-items-center.mb-5           
        .col-lg-4
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img56.png', alt='')               
        .col-lg-8
          .color-fondo-text.bg-color.mb-3(data-aos="fade-down")
            .color-fondo-text__texto 
              p Es un procedimiento para dirigir conversaciones y discusiones que ayudan al moderador a involucrar equitativamente a todos los presentes en una junta. El extenso abanico de procedimientos para moderar reuniones puede ayudar a la construcción de una atmósfera positiva, lograr un reparto justo de los turnos de la palabra y disminuir los conflictos ya existentes.
  
          p(data-aos="fade-down") #[b El moderador de una junta tiene el deber de hacer que los diferentes competidores se impliquen], de manera que se beneficien unos de otros y cada cual ofrezca su aporte para que el trabajo en grupo tenga triunfo.
  
      .bg15.px-5.mb-3.py-3
        .row.justify-content-center.align-items-center.ps-5.mov           
          .col-lg-6.my-3 
            h4.mb-3(data-aos="fade-down") En lo relacionado con el moderador, este:
            ul.lista-ul--color(data-aos="fade-down")
              li.d-flex 
                i.fas.fa-atom
                p.mb-0 Es el líder de la sala que se encarga de hacer que la reunión sea un éxito.
              li.d-flex 
                i.fas.fa-atom
                p.mb-0 Puede tomar medidas necesarias para mantener el orden.
              li.d-flex 
                i.fas.fa-atom
                p.mb-0 Su palabra y criterio serán orientadores y se tomarán como reglas o directrices (que deben ser claras).
              li.d-flex 
                i.fas.fa-atom
                p.mb-0 Los lineamientos ofrecidos por el líder deben ser conocidos por cada uno de los participantes de la reunión.
              li.d-flex 
                i.fas.fa-atom
                p.mb-0 En caso de romperse alguna regla, será el moderador quien actúe y promueva el cumplimiento mediante llamados de atención justos y apropiados.                 
          .col-lg-6 
            img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img57.png', alt='') 
  
      .row.justify-content-center.align-items-center      
        .col-lg-12.pt-5
          .tarjeta.position-relative.rounded-0.bg3.p-4.mb-5(data-aos="flip-down")
            .row.justify-content-center.align-items-center
              .col-lg-2.col-5.mb-lg-0.mb-3
                .imagen-absolute1
                  img(data-aos="zoom-in")(src='@/assets/curso/temas/img3.svg', alt='')
              .col-lg-10
                p(data-aos="fade-down").mb-0.p-3 #[b ¡Atención!] El moderador es un administrador en la reunión, también encargado de la logística, así que si todo sale bien se le reconoce y si todo sale mal, el moderador asume la responsabilidad; un moderador debe saber lidiar con los pensamientos y comportamientos de las personas dentro de una sala donde se procesan temas que pueden llevar al acuerdo o desacuerdo de los integrantes de un equipo.
  
      p(data-aos="fade-down").mb-5 Para llevar a cabo un buen proceso de liderazgo y moderación de actividades, el líder puede aplicar alguna de las siguientes técnicas. En todos los casos, deberá evaluar la pertinencia de las mismas y seleccionar la que considere más adecuada: 
  
      .bg22
        .row.justify-content-center.align-items-center.py-5
          .col-lg-4
            .row.justify-content-center.mb-3.g-0
              .col-lg-2
                div(style='background-color: #F0BD51').p-2.h-100.d-flex.align-items-center
                  img(src='@/assets/curso/temas/img59.svg', alt='' style='width: 68px').m-auto
              .col-lg-10
                div(style='background-color: #FAEBCD').p-3.h-100.brad-lef
                  h4.mb-0 Planear
                  p.mb-0 Planear y controlar el desarrollo de la reunión.
            .row.justify-content-center.mb-3.g-0
              .col-lg-2
                div(style='background-color: #F0BD51').p-2.h-100.d-flex.align-items-center
                  img(src='@/assets/curso/temas/img61.svg', alt='' style='width: 68px').m-auto
              .col-lg-10
                div(style='background-color: #FAEBCD').p-3.h-100.brad-lef
                  h4.mb-0 Establecer
                  p.mb-0 Establece el objetivo de la reunión y recordárselo a los participantes cuando sea necesario. 
            .row.justify-content-center.mb-3.g-0
              .col-lg-2
                div(style='background-color: #F0BD51').p-2.h-100.d-flex.align-items-center
                  img(src='@/assets/curso/temas/img62.svg', alt='' style='width: 68px').m-auto
              .col-lg-10
                div(style='background-color: #FAEBCD').p-3.h-100.brad-lef
                  h4.mb-0 Resumir
                  p.mb-0 Resumir los hechos para que todos los participantes partan de la misma base de conocimiento. 
            .row.justify-content-center.mb-3.g-0
              .col-lg-2
                div(style='background-color: #F0BD51').p-2.h-100.d-flex.align-items-center
                  img(src='@/assets/curso/temas/img63.svg', alt='' style='width: 68px').m-auto
              .col-lg-10
                div(style='background-color: #FAEBCD').p-3.h-100.brad-lef
                  h4.mb-0 Formular
                  p.mb-0 Formular preguntas constructivas orientadas al objetivo. 
            .row.justify-content-center.mb-3.g-0
              .col-lg-2
                div(style='background-color: #F0BD51').p-2.h-100.d-flex.align-items-center
                  img(src='@/assets/curso/temas/img64.svg', alt='' style='width: 68px').m-auto
              .col-lg-10
                div(style='background-color: #FAEBCD').p-3.h-100.brad-lef
                  h4.mb-0 Motivar
                  p.mb-0 Motivar a todos los asistentes a participar.
  
          .col-lg-4
            .row.justify-content-center.mb-3.g-0
              .col-2
                div(style='background-color: #F0BD51').p-2.h-100.d-flex.align-items-center
                  img(src='@/assets/curso/temas/img60.svg', alt='' style='width: 68px').m-auto
              .col-10
                div(style='background-color: #FAEBCD').p-3.h-100.brad-lef
                  h4.mb-0 Contener
                  p.mb-0 Contener a los oradores dominantes.
            .row.justify-content-center.mb-3.g-0
              .col-2
                div(style='background-color: #F0BD51').p-2.h-100.d-flex.align-items-center
                  img(src='@/assets/curso/temas/img65.svg', alt='' style='width: 68px').m-auto
              .col-10
                div(style='background-color: #FAEBCD').p-3.h-100.brad-lef
                  h4.mb-0 Implicar
                  p.mb-0 Implicar a los participantes callados. 
            .row.justify-content-center.mb-3.g-0
              .col-2
                div(style='background-color: #F0BD51').p-2.h-100.d-flex.align-items-center
                  img(src='@/assets/curso/temas/img66.svg', alt='' style='width: 68px').m-auto
              .col-10
                div(style='background-color: #FAEBCD').p-3.h-100.brad-lef
                  h4.mb-0 Controlar
                  p.mb-0 Evitar grandes desviaciones del tema principal hacia temas secundarios. 
            .row.justify-content-center.mb-3.g-0
              .col-2
                div(style='background-color: #F0BD51').p-2.h-100.d-flex.align-items-center
                  img(src='@/assets/curso/temas/img67.svg', alt='' style='width: 68px').m-auto
              .col-10
                div(style='background-color: #FAEBCD').p-3.h-100.brad-lef
                  h4.mb-0 Armonizar
                  p.mb-0 Suavizar las disputas (en caso necesario, mediar entre las partes). 
            .row.justify-content-center.mb-3.g-0
              .col-2
                div(style='background-color: #F0BD51').p-2.h-100.d-flex.align-items-center
                  img(src='@/assets/curso/temas/img68.svg', alt='' style='width: 68px').m-auto
              .col-10
                div(style='background-color: #FAEBCD').p-3.h-100.brad-lef
                  h4.mb-0 Proteger
                  p.mb-0 Conseguir una atmósfera abierta y positiva.
          .col-lg-4.col-8: img.img-t.img-a(src='@/assets/curso/temas/img58.svg', alt='')
  
      .row.justify-content-center.align-items-center.my-5           
        .col-lg-10(data-aos="zoom-in")
          .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.position-relative
            .bloque-texto-g__img(
              :style="{'background-image':`url(${require('@/assets/curso/temas/img1.png')})`}"
            )
              .imagen-superior.position-absolute.mv.px-4(style='bottom:20% ; left: 22%; z-index:2'): img(src='@/assets/curso/temas/img69.svg')
            .bloque-texto-g__texto.px-4.py-5
              p.mb-0.pe-5.pmov En la moderación se usan, de manera sistemática, una secuencia de medios de soporte para el trabajo conjunto, con los cuales se favorece la colaboración de los miembros de una junta. Con el devenir de los tiempos, los procedimientos de moderación fueron evolucionando a partir de los viajes de estudios o el trabajo personal, a los teatros de comercialización o la implementación de sistemas audiovisuales electrónicos. Con todo ello, se ha conseguido un grupo de sistemas complementarios que permite las labores de aprendizaje y trabajo.
  
      p(data-aos="fade-down").mb-5 Para que el equipo esté informado y en constante aprendizaje se implementan diversas estrategias que aportarán a este propósito. Algunas de esas estrategias son:
  
      .bg23
        .row.justify-content-center.align-items-center.py-5           
          .col-lg-3
            ol.lista-ol--cuadro.lista-ol--separador
              li.d-flex 
                .lista-ol--cuadro__vineta
                  span a.
                p.mb-0 #[i Chat] de la empresa.
              li.d-flex 
                .lista-ol--cuadro__vineta
                  span b.
                p.mb-0 Boletines.
              li.d-flex 
                .lista-ol--cuadro__vineta
                  span c.
                p.mb-0 Periódicos murales.
              li.d-flex 
                .lista-ol--cuadro__vineta
                  span d.
                p.mb-0 Conferencias.
              li.d-flex 
                .lista-ol--cuadro__vineta
                  span e.
                p.mb-0 Talleres.           
          .col-lg-3
            ol.lista-ol--cuadro.lista-ol--separador
              li.d-flex 
                .lista-ol--cuadro__vineta
                  span f.
                p.mb-0 Visitas técnicas.
              li.d-flex 
                .lista-ol--cuadro__vineta
                  span g.
                p.mb-0 Entretenimientos.
              li.d-flex 
                .lista-ol--cuadro__vineta
                  span h.
                p.mb-0 Actividades colectivas.
              li.d-flex 
                .lista-ol--cuadro__vineta
                  span i.
                p.mb-0 Acceso a bibliografía actualizada.
              li.d-flex 
                .lista-ol--cuadro__vineta
                  span j.
                p.mb-0 Rotación de puesto.            
          .col-lg-4
            img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img70.png', alt='')
               
      //- .row.justify-content-center.align-items-center      
      //-   .col-lg-12.pt-5
      //-     .tarjeta.position-relative.rounded-0.bg3.p-4.mb-5(data-aos="flip-down")
      //-       .row.justify-content-center.align-items-center
      //-         .col-lg-2.col-5.mb-lg-0.mb-3
      //-           .imagen-absolute1
      //-             img(data-aos="zoom-in")(src='@/assets/curso/temas/img3.svg', alt='')
      //-         .col-lg-10
      //-           p(data-aos="fade-down").mb-0.p-3 #[b ¡Atención!] El moderador es un administrador en la reunión, también encargado de la logística, así que si todo sale bien se le reconoce y si todo sale mal el moderador asume la responsabilidad; un moderador debe saber lidiar con los pensamientos y comportamientos de las personas dentro de una sala donde se procesan temas que pueden llevar al acuerdo o desacuerdo de los integrantes de un equipo.
  
      .row.justify-content-center.align-items-center.my-5           
        .col-lg-10
          TabsC.color-acento-botones
            .py-3.py-md-4(titulo="Presentación del equipo")
              .row.justify-content-center.align-items-center
                .col-11
                  p.mb-0 Una vez que en una junta se fusionan personas que son desconocidas, una presentación del grupo de trabajo es una de las maneras más sencillas para lograr conocerse. Allí, todos los asistentes se van presentando uno a uno con su nombre, su puesto en la organización y ciertos datos acerca de su trayectoria profesional.
  
            .py-3.py-md-4(titulo="Aplicación de las técnicas")
              .row.justify-content-center.align-items-center
                .col-11
                  p.mb-0 Las técnicas de moderación pueden ser aplicadas, cada una de ellas, para mejorar la articulación entre roles y personas, estimular el reconocimiento del liderazgo particular, alcanzar objetivos y procesos exitosos.
      Separador 
      #t_2_3.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
        h2 2.3 Cronogramas de trabajo
  
      .row.justify-content-center.align-items-center.mb-5           
        .col-lg-4
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img71.png', alt='')      
        .col-lg-8
          p(data-aos="fade-down").mb-4 Son una herramienta logística de tareas, diseñada para crear calendarios de trabajo. Se trata de una herramienta o documento en el cual, de forma ordenada, se encuentra la duración de un plan que lleva un orden de fechas y gráficas que ayudan a comprender más sencillamente su contenido.
          .imgs-flotantes
            img.img-flotante(data-aos="zoom-in")(src='@/assets/curso/temas/flotante2.svg', alt='Imagen decorativa')
            .tarjeta-avatar-b.mb-5.pt-1
              .tarjeta-avatar-b__img
                img.img-a.img-t(src='@/assets/curso/temas/img72.svg' alt='AvatarTop')
              .tarjeta.tarjeta--azul.bg24
                .p-4.ps-0
                  p(data-aos="fade-down").mb-0 El cronograma de trabajo representa las labores que debe cumplir cada uno, clasificándolas en fases que cuentan con su respectiva fecha de ejecución. Es así como se convierte en herramienta de mucha utilidad para el desarrollo de proyectos.
  
      p(data-aos="fade-down").mb-5 En el siguiente video se muestran las generalidades y aspectos clave que se deben conocer sobre los cronogramas de trabajo.
  
      .row.justify-content-center.align-items-center.mb-5           
        .col-lg-12(data-aos="fade-left")     
          figure
            .video
              iframe(width="560" height="315" src="https://www.youtube.com/embed/VZs-w3WZqwk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)   
          figcaption Video. Cronogramas de trabajo
  
      Separador 
      #t_2_4.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
        h2 2.4 Conceptos, tipos y características 
  
      p(data-aos="fade-down") Cuando se habla de un cronograma de trabajo, se hace referencia a una herramienta para diseñar calendarios de trabajo, el cual permite obtener información de manera ordenada, donde se vean las funciones de cada uno y el tiempo que tiene para su desarrollo. 
      p(data-aos="fade-down").mb-5 En la actualidad, existen varios tipos de cronograma con características particulares. Entre los más comunes y usados se pueden mencionar: 
      .bg22
        .row.justify-content-center.align-items-stretch       
          .col-lg-3.col-md-6.col-sm-6.my-3
            .row.justify-content-center.align-items-stretch       
              .col-5.bg7.bgl7.px-0(data-aos="fade-right")
                .p-2
                  img.img-a.img-t.py-1(data-aos="zoom-in")(src='@/assets/curso/temas/img73.svg', alt='')
              .col-7.bg8.px-0(data-aos="fade-left")
                .p-2
                  h5.ps-3(data-aos="fade-down").mb-0 Gráfico de Gantt 
          .col-lg-3.col-md-6.col-sm-6.my-3
            .row.justify-content-center.align-items-stretch       
              .col-5.bg7.bgl7.px-0(data-aos="fade-right")
                .p-2
                  img.img-a.img-t.py-1(data-aos="zoom-in")(src='@/assets/curso/temas/img74.svg', alt='')
              .col-7.bg8.px-0(data-aos="fade-left")
                .p-2
                  h5.ps-3(data-aos="fade-down").mb-0 Diagrama de Pert
          .col-lg-3.col-md-6.col-sm-6.my-3
            .row.justify-content-center.align-items-stretch       
              .col-5.bg7.bgl7.px-0(data-aos="fade-right")
                .p-2
                  img.img-a.img-t.my-1(data-aos="zoom-in")(src='@/assets/curso/temas/img75.svg', alt='')
              .col-7.bg8.px-0(data-aos="fade-left")
                .p-2
                  h5.ps-3(data-aos="fade-down").mb-0 Cronograma de investigación
          .col-lg-3.col-md-6.col-sm-6.my-3
            .row.justify-content-center.align-items-stretch       
              .col-5.bg7.bgl7.px-0(data-aos="fade-right")
                .p-2
                  img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img76.svg', alt='')
              .col-7.bg8.px-0(data-aos="fade-left")
                .p-2
                  h5.ps-3(data-aos="fade-down").mb-0 Cronograma de trabajo 
  
        .row.justify-content-center.align-items-stretch       
          .col-lg-3.col-md-6.col-sm-6.my-3
            .row.justify-content-center.align-items-stretch       
              .col-5.bg7.bgl7.px-0(data-aos="fade-right")
                .p-2
                  img.img-a.img-t.py-1(data-aos="zoom-in")(src='@/assets/curso/temas/img77.svg', alt='')
              .col-7.bg8.px-0(data-aos="fade-left")
                .p-2
                  h5.ps-3(data-aos="fade-down").mb-0 Cronograma de hitos
          .col-lg-3.col-md-6.col-sm-6.my-3
            .row.justify-content-center.align-items-stretch       
              .col-5.bg7.bgl7.px-0(data-aos="fade-right")
                .p-2
                  img.img-a.img-t.py-1(data-aos="zoom-in")(src='@/assets/curso/temas/img78.svg', alt='')
              .col-7.bg8.px-0(data-aos="fade-left")
                .p-2
                  h5.ps-3(data-aos="fade-down").mb-0 Microsoft Project
          .col-lg-3.col-md-6.col-sm-6.my-3
            .row.justify-content-center.align-items-stretch       
              .col-5.bg7.bgl7.px-0(data-aos="fade-right")
                .p-2
                  img.img-a.img-t.my-1(data-aos="zoom-in")(src='@/assets/curso/temas/img79.svg', alt='')
              .col-7.bg8.px-0(data-aos="fade-left")
                .p-2
                  h5.ps-3(data-aos="fade-down").mb-0 Cronograma de inversiones
          .col-lg-3.col-md-6.col-sm-6.my-3
            .row.justify-content-center.align-items-stretch       
              .col-5.bg7.bgl7.px-0(data-aos="fade-right")
                .p-2
                  img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img80.svg', alt='')
              .col-7.bg8.px-0(data-aos="fade-left")
                .p-2
                  h5.ps-3(data-aos="fade-down").mb-0 Cronograma Pay
  
      h5(data-aos="fade-down").my-5 Un cronograma cuenta con ciertas propiedades, las cuales se deben tener en cuenta para su creación, estas son:
  
      SlyderF.slyder-100.my-5(columnas="col-lg-6 col-xl-4")(data-aos="fade-right")
        .row.justify-content-center.align-items-stretch.crd.crd--100       
          .col-5.bg25.bgl7.px-0(data-aos="fade-right")
            .p-2
              img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img81.svg', alt='')
          .col-7.bg26.px-0(data-aos="fade-left")
            .p-2
              p.ps-3(data-aos="fade-down").mb-0 Debe estar completo.
  
        .row.justify-content-center.align-items-stretch.crd.crd--100       
          .col-5.bg25.bgl7.px-0(data-aos="fade-right")
            .p-2
              img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img82.svg', alt='')
          .col-7.bg26.px-0(data-aos="fade-left")
            .p-2
              p.ps-3(data-aos="fade-down").mb-0 Debe ser realista.
  
        .row.justify-content-center.align-items-stretch.crd.crd--100       
          .col-5.bg25.bgl7.px-0(data-aos="fade-right")
            .p-2
              img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img83.svg', alt='')
          .col-7.bg26.px-0(data-aos="fade-left")
            .p-2
              p.ps-3(data-aos="fade-down").mb-0 Debe considerar la decisión de cada integrante del equipo.
  
        .row.justify-content-center.align-items-stretch.crd.crd--100       
          .col-5.bg25.bgl7.px-0(data-aos="fade-right")
            .p-2
              img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img84.svg', alt='')
          .col-7.bg26.px-0(data-aos="fade-left")
            .p-2
              p.ps-3(data-aos="fade-down").mb-0 Debe ser pactado.
  
        .row.justify-content-center.align-items-stretch.crd.crd--100       
          .col-5.bg25.bgl7.px-0(data-aos="fade-right")
            .p-2
              img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img85.svg', alt='')
          .col-7.bg26.px-0(data-aos="fade-left")
            .p-2
              p.ps-3(data-aos="fade-down").mb-0 Deberá ser formalizado y divulgado.
      h5(data-aos="fade-down").mb-5 En relación con los conceptos, tipos y características de los cronogramas de trabajo se debe tener en cuenta las siguientes generalidades:
  
      AcordionA(tipo="a" clase-tarjeta="tarjeta bg27")(data-aos="fade-right")
        .row.justify-content-center.align-items-start(titulo="Determinación de los elementos")
          .col-lg-7
            p Es fundamental que se determinen ciertos elementos y aspectos configurativos, tales como la duración de cada labor, ya que así es como los gráficos trabajan mayormente.
          .col-lg-4
            img.img-a.img-t(src='@/assets/curso/temas/img86.png', alt='')
        .row.justify-content-center.align-items-start(titulo="Seguimiento")
          .col-lg-7
            p Contar con un cronograma de trabajo ayuda a llevar un mejor seguimiento y control de las actividades que se están realizando. Ello favorece la labor de supervisión y evita retrasos o tareas faltantes. 
          .col-lg-4
            img.img-a.img-t(src='@/assets/curso/temas/img87.png', alt='')
        .row.justify-content-center.align-items-start(titulo="Consideración de recursos")
          .col-lg-7
            p El cronograma permite tener la mejor manera de saber qué recursos faltan o existen a la mano para el desarrollo del proyecto. Con ello, se pueden controlar las actividades de cada uno de los integrantes y el tiempo. Además, se anticipan acciones para los retrasos que se pueden provocar por cualquier motivo.
          .col-lg-4
            img.img-a.img-t(src='@/assets/curso/temas/img88.png', alt='')
        .row.justify-content-center.align-items-start(titulo="Mirada transversal")
          .col-lg-7
            p El cronograma dentro de una empresa ofrece un panorama global de las áreas de la empresa y sus desempeños: quién sí y quién no está cumpliendo las metas, etc. Es por eso que se debe seleccionar el cronograma que más se acomode a la empresa o proyecto.
          .col-lg-4
            img.img-a.img-t(src='@/assets/curso/temas/img89.png', alt='')
        .row.justify-content-center.align-items-start(titulo="Ventajas")
          .col-lg-7
            p Algunas de las ventajas que se pueden obtener con la elaboración de un cronograma apropiado son: orden de las tareas, supervisión de la proactividad, análisis del avance y estado de las actividades y procesos.
          .col-lg-4
            img.img-a.img-t(src='@/assets/curso/temas/img90.png', alt='')
        .row.justify-content-center.align-items-start(titulo="Riesgos")
          .col-lg-7
            p Un cronograma corre con ciertos riesgos, ya que el margen de tiempo que se establece a veces no llega a favorecer, pues al ser diseñado no se tiene en cuenta factores externos que puedan afectar el desarrollo de algunas tareas. No obstante, son factores que pueden ser controlados en la gran mayoría de los casos.
          .col-lg-4
            img.img-a.img-t(src='@/assets/curso/temas/img91.png', alt='')
        .row.justify-content-center.align-items-start(titulo="Tipos")
          .col-lg-7
            p Los tipos de cronograma más comunes y usados suelen ser: plan narrado, barras de Gantt, método de la ruta crítica y cronograma lineal.
          .col-lg-4
            img.img-a.img-t(src='@/assets/curso/temas/img92.png', alt='')
  
  
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

<style lang="sass">
.bloque-texto-g
  justify-content: flex-start
  background-color: rgba(255, 255, 255, 0.65)
.bloque-texto-g__img
  left: auto
  right: 0
</style>
