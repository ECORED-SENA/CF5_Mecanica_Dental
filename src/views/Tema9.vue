<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 9
      h1 Prescripción clínica
    
    .row.justify-content-center.mb-5
      .col-lg-5.col-10.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema9/img01.png')
      .col-lg-7
        p Es la indicación dada por un profesional en odontología a partir del diagnóstico establecido a un paciente sobre el tipo y características del dispositivo médico sobre medida bucal que requiere ser fabricado. La prescripción deberá estar sustentada en una evaluación previa del paciente, se realizará en idioma español, en forma escrita, sea manuscrita, mecanográfica, medio electromagnético o computarizada.
        .cajon.color-acento-contenido.p-4(data-aos="fade-left")
          p.mb-0 Los dispositivos médicos sobre medida bucal que se fabrican en el territorio nacional deben ser prescritos por los profesionales en odontología, como prestadores de servicios de salud responsables del proceso en los términos señalados en la resolución. Las entidades promotoras de salud, entidades que administren planes adicionales de salud, las entidades adaptadas de salud, las entidades pertenecientes al Régimen Especial y de Excepción de salud, y las Entidades territoriales cuando contraten con Empresas Sociales del Estado debidamente habilitadas, la atención de la población pobre no asegurada y lo no cubierto por subsidios a la demanda, respetarán la autonomía del odontólogo en la prescripción, acorde con las necesidades del paciente y la tecnología, según el caso (Resolución 2113 de 2021).
    
    .row.justify-content-center.align-items-center.mb-4
      .col-md-4.mb-md-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema9/img02.jpg')
      .col-md-8(data-aos="fade-left")
        .h5 La prescripción clínica no podrá contener enmendaduras o tachaduras, siglas, claves, abreviaturas o símbolos, diferentes a los estipulados en Lex - Artis o convenciones internacionales y contendrá la siguiente información:
        ul.lista-ul--color.ms-4
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            p.mb-0 Nombre legible del prestador de servicios de salud, dirección, número telefónico o dirección electrónica, número de registro profesional de quien prescribe.
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            p.mb-0 Lugar y fecha de la prescripción.
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            p.mb-0 Nombre del paciente y documento de identificación.
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            p.mb-0 Número de la historia clínica.
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            p.mb-0 Nombre del dispositivo médico sobre medida prescrito con sus características.
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            p.mb-0 Indicaciones que a su juicio considere el prescriptor (consideraciones anatómicas, fisiológicas, etc.).
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            p.mb-0 Vigencia de la prescripción. La prescripción del dispositivo médico sobre medida bucal vence en seis (6) meses. Una vez transcurrido este tiempo, y al no haber concluido el trabajo, es necesario una nueva valoración del paciente y con fundamento a lo cual se determinará iniciar nuevamente el proceso de fabricación.
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            p.mb-0 Firma del odontólogo tratante.

    .BGM17.p-md-5.p-4
      .h5.text-center.mb-5 Para finalizar, se presenta la estructura de una prescripción clínica que será diligenciada por el odontólogo:
      .titulo-sexto.color-acento-contenido.mb-4
        h5 Figura 5
        span Estructura prescripción clínica
      figure
        img(src='@/assets/curso/tema9/img03.png')
    

</template>

<script>
export default {
  name: 'Tema9',
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
