<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Residuos sólidos
    
    p.mb-5 Los establecimientos que fabrican y reparan dispositivos médicos sobre medida bucal deben contar con procedimientos para el manejo integral de residuos sólidos y líquidos, cumpliendo la normatividad vigente para la materia.

    .row.justify-content-center.align-items-center.BG10.mb-5
      .col-md-6.col-10.mb-md-0.mb-4.px-0(data-aos="fade-right")
        img(src='@/assets/curso/tema4/img01.png')
      .col-md-6.p-5
        p Los desechos sólidos previo a su recolección deberán ser clasificados inmediatamente después de su generación en el mismo lugar de origen. Todos los recipientes para almacenamiento temporal deben estar rotulados con el nombre de la sección a la que pertenecen y la clase de residuo que contienen, para la segregación en la fuente de los residuos sólidos se dispondrá de cuatro tipos de bolsas: verdes (orgánico), negro (no reciclables), blancas (reciclables) y rojas (residuos peligrosos); estas bolsas deben ser selladas, marcadas e identificadas con los sellos adhesivos que se entregan a cada una de las dependencias.

    .cajon.color-acento-contenido.p-4.mb-5(data-aos="fade-right")
      p.mb-0 Cabe manifestar que los objetos cortopunzantes, previo a ser colocados en las fundas rojas deberán ser almacenados en recipientes de plástico rígido, resistente y opaco (guardianes).

    .row.justify-content-center.mb-5
      .col-lg-3.col-sm-6.col-8.mb-lg-0.px-1.mb-4(data-aos="fade-right")
        .tarjeta.tarjeta-slide.arriba.BG11(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-3
              h4 Reciclables
              p.mb-5 #[strong Blanca]: todo material susceptible para reciclado, reutilizado (vidrio, plástico, papel, cartón, entre otros).
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema4/img02.svg')})`}")
      .col-lg-3.col-sm-6.col-8.mb-lg-0.px-1.mb-4(data-aos="zoom-in")
        .tarjeta.tarjeta-slide.arriba.BG12(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-3
              h4.text-white No reciclables, no peligrosos
              p.mb-5.text-white #[strong Negra]: todo residuo no reciclable.
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema4/img03.svg')})`}")
      .col-lg-3.col-sm-6.col-8.mb-lg-0.px-1.mb-4(data-aos="zoom-in") 
        .tarjeta.tarjeta-slide.arriba.BG13(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-3
              h4.text-white Orgánicos
              p.mb-5.text-white #[strong Verde]: origen biológico, restos de comida, cáscaras de fruta, verduras, hojas, pasto, entre otros. Susceptible de ser aprovechado.
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema4/img04.svg')})`}")
      .col-lg-3.col-sm-6.col-8.mb-lg-0.px-1.mb-4(data-aos="fade-left") 
        .tarjeta.tarjeta-slide.arriba.BG14(@mouseover="indicadorTarjetaSlide = false")
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-3
              h4.text-white Peligrosos
              p.mb-5.text-white #[strong Roja]: residuos (corrosivo, reactivo, tóxico, inflamable, biológico infeccioso).
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/tema4/img05.svg')})`}")

    p Los residuos sólidos de laboratorio dental son clasificados en residuos infecciosos, residuos tóxicos no infecciosos y residuos domésticos y los desechos sospechosos de contener el patógeno en concentración suficiente que causan enfermedades en huéspedes susceptibles se consideran desechos infecciosos. 

    .BGM15.p-4.p-md-5
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-4
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/tema4/img06.jpg')})`}"
        )(data-aos="fade-right")
        .bloque-texto-g__texto.p-4(data-aos="fade-left")
          p.mb-0 Los retenedores, los bloques de mordida oclusales, los registros oclusales y los aparatos de ortodoncia entran en contacto de forma rutinaria con la saliva y la sangre humana. Algunos estudios indican la existencia de bacterias en las pastas. Los otros residuos infecciosos incluyen siliconas utilizadas para prótesis maxilofaciales, guantes y envases de plástico utilizados para el transporte de prótesis y los aparatos desde las clínicas.

      .row.justify-content-center.align-items-center.mb-5
        .col-lg-5.order-lg-1.order-2(data-aos="fade-right")
          p Los desechos tóxicos no infecciosos están desprovistos de contaminación por fluidos humanos, pero son potencialmente tóxicos por naturaleza; incluye los #[strong desechos de resina acrílica, aleaciones metálicas desechadas, polvo metálico, porcelana y desechos de yeso]. Otros desechos tóxicos no infecciosos son las aleaciones de amalgama y los ácidos utilizados en el pulido electrolítico de estructuras metálicas. Los residuos de tipo doméstico están compuestos por vasos de papel, plásticos y lijas.
        .col-lg-5.col-10.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
          img(src='@/assets/curso/tema4/img07.jpg')
        
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-5.order-lg-1.order-2(data-aos="fade-right")
          p Como se vio antes, el odontólogo genera una impresión de la cavidad oral del paciente utilizando materiales de impresión para reproducir los puntos de referencia necesarios para la fabricación de una prótesis o un aparato dental. El material de impresión colocado en una cubeta de impresión se desinfectará y se envolverá en papel plastificado cerrado con un paño húmedo o una almohadilla de algodón para mantener la humedad durante el transporte al laboratorio dental designado. Estas impresiones forman parte de los residuos sólidos del laboratorio dental.
        .col-lg-5.col-10.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
          img(src='@/assets/curso/tema4/img08.jpg')
  
    p En el acabado y pulido después de que el modelo ha sido fundido dan como resultado la producción de varios tipos de desechos que generalmente se eliminan en los contenedores de basura. Algunos desechos sólidos del laboratorio dental se recuperan de trampas para desechos sólidos instaladas debajo de los fregaderos, mientras que otros desechos se eliminan en el sistema de alcantarillado. 
    p.mb-5 Los materiales que suelen quedar atrapados de esta manera son el yeso de los pulidores de modelos y el exceso de mezcla sobre el fregadero, los materiales de revestimiento, la piedra pómez, la arena y la cera que se ha hervido de las muflas para dentaduras postizas o de los modelos de trabajo. A continuación, se presenta una tabla donde se clasifica este tipo de desechos. 
    
    .row.justify-content-center.mb-4
      .col-md-10.mb-4(data-aos="zoom-in")
        .titulo-sexto.color-acento-contenido.mb-5
          h5 Tabla 2
          span Residuos en el laboratorio dental
        .tabla-a.color-acento-contenido.mb-5
          table
            thead
              tr
                th Residuos infecciosos y potencialmente infeccioso
                th Residuos tóxicos no infecciosos
                th Residuos domésticos
            tbody
              tr
                td Residuos que han entrado en contacto con saliva humana y posiblemente con sangre. Un ejemplo serían los materiales de impresión.
                td Se compone principalmente de aleaciones de fundición como cromo (Cr), níquel (Ni), plata (Ag) y otros metales. Estos metales se descartan ya sea como polvo del esmerilado o como botones sobrantes de la fundición.
                td Los productos de yeso y los diferentes tipos de cera se incluyen junto con los residuos orgánicos y de oficina.


</template>

<script>
export default {
  name: 'Tema4',
  data: () => ({
    indicadorTarjetaSlide: true,
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
