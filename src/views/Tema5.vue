<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Organigrama estructural organizacional
    
    .row.align-items-center.mb-4
      .col-md-1.col-2(data-aos="fade-right")
        img(src="@/assets/curso/temas/img04.png")
      .col-md-11.col-10
        p.mb-0 Un laboratorio dental es, quizás, uno de los negocios comerciales más importantes de cualquier práctica dental. El laboratorio fabrica la prótesis dental ordenada por profesionales dentales, por ello debe estar organizado. En el organigrama deben estar definidos los roles y responsabilidades de cada miembro del equipo y área del laboratorio. A continuación, se presenta la estructura general de un laboratorio dental:

    .row.justify-content-center.mb-4(data-aos="zoom-in")
      .col-md-10
        .titulo-sexto.color-acento-contenido.mb-4
          h5 Figura 3
          span Organigrama laboratorio dental 
        img(src="@/assets/curso/tema5/img01.svg")

    .BGM09.p-4.p-md-5
      p.text-center Para profundizar en esta estructura, en el siguiente recurso se aborda cada parte de la misma.  

      SlyderB.mb-5(:datos="datosSlyder")
        
</template>

<script>
export default {
  name: 'Tema5',
  data: () => ({
    datosSlyder: [
      {
        titulo: 'Área administrativa',
        texto:
          'Se encarga de supervisar las operaciones diarias del laboratorio para garantizar la eficiencia y el flujo de trabajo fluido.',
        imagen: require('@/assets/curso/tema5/img02.jpg'),
      },
      {
        titulo: 'Director técnico',
        texto:
          'Debe prestar sus servicios con vocación de permanencia en el establecimiento, contar con diploma de tecnólogo en mecánica dental, o de técnico profesional en mecánica dental, o certificado de técnico laboral, otorgado por una institución de educación autorizada en el territorio nacional.',
        imagen: require('@/assets/curso/tema5/img03.jpg'),
      },
      {
        titulo: 'Personal técnico',
        texto:
          'Participa en la fabricación del dispositivo médico, siguiendo procedimientos establecidos para el proceso de fabricación y bajo la supervisión del director técnico.',
        imagen: require('@/assets/curso/tema5/img04.jpg'),
      },
      {
        titulo: 'Área de recepción',
        texto:
          'Es el área donde se reciben los trabajos, impresiones, modelos, pruebas de prótesis, etc. Sus trabajadores deben atenerse a las medidas generales de prevención de infecciones. Deben usar guantes, gafas, mascarillas.',
        imagen: require('@/assets/curso/tema5/img05.jpg'),
      },
      {
        titulo: 'Área de desinfección',
        texto:
          'En esta zona se esterilizan los trabajos recibidos si no lo están. Las superficies de trabajo se limpiarán sistemáticamente con una solución de hipoclorito sódico y lejía doméstica para eliminar restos orgánicos.',
        imagen: require('@/assets/curso/tema5/img06.jpg'),
      },
      {
        titulo: 'Zona de fabricación',
        texto:
          'Contará con el mobiliario adecuado al trabajo que se va a desarrollar; con los puntos de luz adecuados al número de puestos de trabajo; y con el sistema de aspiración para aquellas fases de elaboración que lo requieran.',
        imagen: require('@/assets/curso/tema5/img07.jpg'),
      },
      {
        titulo: 'Área de yesos',
        texto:
          'Es el área donde se trabajó el modelo de estudio de ortodoncia definitiva. Se realiza el vaciado de los modelos con yeso, preparación de los modelos para su posterior montaje en articulador, duplicación de los mismos, enmuflado, entre otros.',
        imagen: require('@/assets/curso/tema5/img08.jpg'),
      },
      {
        titulo: 'Área de fundición y arenado',
        texto:
          'Este es un espacio con un condicionamiento especial para fundir metal, utilizar centrifugas, sopletes de gas-aire, de oxiacetileno. Después de obtenido el metal, se procede al arenado que es una técnica de aire a presión con arena, para dejar las prótesis libre de residuos.',
        imagen: require('@/assets/curso/tema5/img09.jpg'),
      },
      {
        titulo: 'Pulido',
        texto:
          'Área destinada para pulir todas las prótesis dentales confeccionadas en el laboratorio.',
        imagen: require('@/assets/curso/tema5/img10.jpg'),
      },
      {
        titulo: 'Área de almacén',
        texto:
          'Aquí se tienen registradas las materias primas y emplearlas según su fecha de caducidad.',
        imagen: require('@/assets/curso/tema5/img11.jpg'),
      },
      {
        titulo: 'Zona de registro',
        texto:
          'Es la zona del laboratorio que estará dotada del mobiliario adecuado para realizar las tareas administrativas y de archivo documental de los productos fabricados.',
        imagen: require('@/assets/curso/tema5/img12.jpg'),
      },
    ],
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
