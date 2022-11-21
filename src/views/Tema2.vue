<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Buenas prácticas BPM y BPE
    
    p.mb-5 Buenas Prácticas de Manufactura (BPM) y Buenas Prácticas de Elaboración (BPE) son los principios básicos y prácticas que permiten obtener productos de óptima calidad cumpliendo normas de higiene y seguridad y mejorar la productividad en el laboratorio, esto se logra mediante:

    .row.justify-content-center.mb-4
      .col-md-10.mb-4(data-aos="zoom-in")
        .titulo-sexto.color-acento-contenido.mb-4
          h5 Figura 1
          span Buenas prácticas BPM y BPE
        ImagenInfografica.color-primario.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema2/img01.svg')
          .tarjeta.color-secundario.p-3(x="10.7%" y="12.8%" numero="1")
            .h4 Mantenimiento de áreas, equipo e instalaciones
            p - Diseño y construcción.
            p - Limpieza y desinfección de áreas e instalaciones.
          .tarjeta.color-secundario.p-3(x="10.7%" y="27.8%" numero="2")
            .h4 Operación con personal calificado
            p - El personal técnico debe tener certificado de estudios.
          .tarjeta.color-secundario.p-3(x="10.7%" y="42.8%" numero="3")
            .h4 Control y manejo de residuos, vertimientos y emisiones
            p - Disposición de residuos sólidos.
            p - Clasificación de residuos sólidos.
            p - Los residuos se suelen clasificar como orgánicos, inorgánicos y peligrosos.
          .tarjeta.color-secundario.p-3(x="10.7%" y="57.8%" numero="4")
            .h4 Identificación y control de riesgos y/o contaminación
            p Los productos y el personal manipulador, pueden ser sometidos a diversos riesgos y contaminantes que pueden afectar considerablemente la inocuidad del producto, su seguridad y el bienestar laboral de las personas que desarrollen las operaciones.
          .tarjeta.color-secundario.p-3(x="10.7%" y="72.8%" numero="5")
            .h4 Control y seguimiento a procesos de distribución
            p El transporte de los aparatos debe realizarse en condiciones que excluyan la contaminación y/o la proliferación de microorganismos y plagas, para así prevenir la alteración de aparato dental.
          .tarjeta.color-secundario.p-3(x="10.7%" y="87.8%" numero="6")
            .h4 Gestión documental y registros
            p La gestión documental tiene el objetivo de definir los procedimientos y los controles empleados de: Limpieza y órdenes de trabajo para la fabricación de aparatos.

      .col-md-10.mb-4(data-aos="fade-right")
        .cajon.color-acento-contenido.p-4
          p Las buenas prácticas de fabricación son prácticas que están diseñadas para prevenir errores o accidentes, y su objetivo es evitar la contaminación del producto terminado. Para los aparatos de ortopedia funcional se debe diseñar, preparar, elaborar, fabricar y reparar aparatos de ortodoncia y férulas oclusales, teniendo en cuenta los siguientes pasos: 
      
      .col-md-10.mb-4(data-aos="zoom-in")
        PasosA.color-acento-contenido(tipo="n")
          .row.justify-content-center.align-items-center
            .col-md-8.order-md-1.order-2
              p Realizar el vaciado de las impresiones con yeso, los zocolados de los modelos con los moldes y las técnicas de recortado adecuadas, para los estudios previos de ortodoncia y el montaje de los modelos en el articulador. 
            .col-md-4.col-8.order-md-2.order-1.mb-md-0.mb-4
              img(src='@/assets/curso/tema2/img02.png')
          .row.justify-content-center.align-items-center
            .col-md-4.col-8.mb-md-0.mb-4
              img(src='@/assets/curso/tema2/img03.png')
            .col-md-8
              p Realizar con precisión las estructuras que actúan como retenedores, estabilizadores y elementos activos en aparatos de ortodoncia removibles y fijas; con alambre, arcos, y bandas metálicas de diversos calibres, secciones y grado de rigidez del material. 
          .row.justify-content-center.align-items-center
            .col-md-8.order-md-1.order-2
              p Incorporar el material acrílico en aparatos removibles o  los elementos de unión en ortodoncia fija, según los requisitos del aparato de ortodoncia y, en su caso, realizar el proceso de polimerización y/o los procesos de fijación y/o soldadura con la técnica seleccionada. 
            .col-md-4.col-8.order-md-2.order-1.mb-md-0.mb-4
              img(src='@/assets/curso/tema2/img04.png')
          .row.justify-content-center.align-items-center
            .col-md-4.col-8.mb-md-0.mb-4
              img(src='@/assets/curso/tema2/img05.png')
            .col-md-8
              p Comprobar y activar, si procede sobre los aparatos de ortodoncia realizados, la funcionalidad, la fuerza ejercida, la retención de los elementos elaborados y su estabilidad en relación con el producto prescrito. 
          .row.justify-content-center.align-items-center
            .col-md-8.order-md-1.order-2
              p Realizar férulas oclusales con los modelos montados en un articulador semiajustable, según los registros que permiten programar los valores individuales del paciente.
            .col-md-4.col-8.order-md-2.order-1.mb-md-0.mb-4
              img(src='@/assets/curso/tema2/img06.png')

    .BGM03.p-4.p-md-5(data-aos="fade-right")
      .row.justify-content-center.align-items-center.p-4
        .col-md-4.col-8.mb-md-0.mb-4
          img(src='@/assets/curso/tema2/img07.png')
        .col-md-8
          .h4 Es importante saber que un laboratorio dental debe establecer Buenas Prácticas de Manufactura en donde: 
          ul.lista-ul--color.ms-4
            li
              <i class="fas fa-dot-circle" style="color:#0273BC"></i>
              | Se establecen diversas especificaciones y controles para los dispositivos.
            li
              <i class="fas fa-dot-circle" style="color:#0273BC"></i>
              | Los dispositivos se diseñan bajo un sistema de calidad para cumplir con estas especificaciones.
            li
              <i class="fas fa-dot-circle" style="color:#0273BC"></i>
              | Los dispositivos están fabricados bajo un sistema de calidad.
            li
              <i class="fas fa-dot-circle" style="color:#0273BC"></i>
              | Los dispositivos estén correctamente instalados, revisados y reparados.
            li
              <i class="fas fa-dot-circle" style="color:#0273BC"></i>
              | Los datos de calidad se analizan para identificar y corregir problemas de calidad.


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

<style lang="sass"></style>
