<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 8
      h1 Documentación y archivo
    
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema8/img01.jpg')})`}"
      )(data-aos="fade-right")
      .bloque-texto-g__texto.p-4(data-aos="fade-left")
        p.mb-0 Según la normatividad que rige a los laboratorios dentales en Colombia, es importante tener en cuenta que todo producto elaborado debe contar con un proceso de documentación y archivo; por tal razón, en el artículo 22 de la Resolución 2113 de 2021 por la cual se establece la documentación, archivo y procedimientos generales, así los establecimientos deberán cumplir con lo siguiente:
    
    .row.justify-content-center.mb-4
      .col-md-6.col-10.mb-md-0.mb-4(data-aos="fade-right")
        .tarjeta-avatar
          img(src='@/assets/curso/tema8/img02.png' alt='AvatarTop')
          .BGR18.p-4.py-5
            .h4.text-center.mt-5 Documentación
            p Es aquella información esencial para la trazabilidad del dispositivo médico durante su vida útil y debe estar relacionada con el proceso de fabricación. Esta información debe contener como mínimo: nombre del paciente, nombre del odontólogo, fecha de fabricación, código y nombre del producto según clasificación internacional que acoja el país.
            p Está permitido registrar la información por medio de sistemas electrónicos de procesamiento de datos, o sistemas fotográficos u otros medios aprobados, siempre y cuando la información esté protegida de posibles modificaciones por personal no autorizado.
      .col-md-6.col-10.mb-md-0.mb-4(data-aos="fade-left")
        .tarjeta-avatar
          img(src='@/assets/curso/tema8/img03.png' alt='AvatarTop')
          .BGR03.p-4.py-5
            .h4.text-center.mt-5 Archivo
            p El archivo relacionado con el dispositivo médico debe estar vigente y en el establecimiento por un periodo de cinco (5) años con los siguientes documentos:
            ul.lista-ul--color.ms-4
              li
                <i class="fas fa-dot-circle" style="color:#0273BC"></i>
                | Prescripción odontológica, con el diseño del dispositivo médico.
              li
                <i class="fas fa-dot-circle" style="color:#0273BC"></i>
                | Registros del control de calidad de puntos críticos.
              li
                <i class="fas fa-dot-circle" style="color:#0273BC"></i>
                | Garantía.
              li
                <i class="fas fa-dot-circle" style="color:#0273BC"></i>
                p.mb-4 Ficha técnica.

    p #[strong Procedimientos generales]: los establecimientos que fabrican y reparan dispositivos médicos sobre medida bucal deben contar con los siguientes procedimientos generales con sus registros:

    .row.justify-content-center.mb-4
      .col-md-4.col-8.mb-md-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema8/img04.png')
      .col-md-8
        ul.lista-ul--color.ms-4
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            | Procedimiento de recepción, limpieza y desinfección de modelos o impresiones y material enviado por el prestador de salud. 
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            |Procedimiento de alistamiento y despacho del dispositivo médico terminado al odontólogo tratante. 
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            |Procedimiento general para manejo y almacenamiento de materias primas y del dispositivo médico, incluye: recepción, calificación del estado de calidad y destino de materias primas y del dispositivo médico terminado, eliminación de dispositivos que no cumplan con los requisitos de calidad.
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            |Procedimiento para la capacitación del personal y su evaluación periódica. 
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            |Procedimiento relacionado con aseo y limpieza del establecimiento, control de plagas y roedores. 
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            |Procedimiento para el manejo integral de residuos sólidos y líquidos, cumpliendo la normatividad vigente para la materia. 
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            |Procedimiento para el mantenimiento preventivo de equipos, máquinas y herramientas. 
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            |Procedimiento relacionado con el tratamiento a quejas, reclamos y notificaciones de eventos adversos acorde al Programa de Tecnovigilancia.


</template>

<script>
export default {
  name: 'Tema8',
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
