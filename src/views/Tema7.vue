<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 7
      h1 Portafolio de servicios
    
    .row.justify-content-between.align-items-center.BG16.p-5.mb-4
      .col-lg-6.order-lg-1.order-2(data-aos="fade-right")
        p Para los laboratorios dentales, así como en los establecimientos prestadores de servicios, es importante una excelente presentación de los productos o servicios que ofrece a un determinado mercado, por tal razón, las empresas realizan un sinnúmero de estrategias para hacerse notar y atraer clientes; entre las más conocidas se encuentra un documento o carpeta en el que se incluye la información básica y necesaria del	negocio o empresa para que nuestros clientes o futuros clientes conozcan nuestra empresa, ayudándoles a tener una buena impresión de ella.
        a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=hETivH98gc0&ab_channel=EcosistemadeRecursosEducativosDigitalesSENA" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            p En el siguiente video podrán encontrar más información sobre los portafolios.
      .col-lg-5.col-10.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        img(src='@/assets/curso/tema7/img01.png')

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-4.col-8.mb-lg-0.mb-4(data-aos="fade-right")
        img(src='@/assets/curso/tema7/img02.jpg')
      .col-lg-8(data-aos="fade-left")
        p El portafolio puede tener un aspecto o formato diferente según las necesidades de cada laboratorio; no existe una apariencia o enfoque universalmente aceptado. Algunos son recursos similares a revistas diseñadas, mientras que otros son archivos PDF bien organizados.
        p La mayoría de los catálogos de productos incorporarán varios elementos básicos que utilizan datos de productos. 
        .h5 Estos son algunos tipos de información que es visible en un portafolio de productos:
        ul.lista-ul--color.ms-4
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            p.mb-0 <span style="color:#0273BC">#[strong Nombre del producto]</span>: el nombre por el cual el proveedor y el cliente hacen referencia al producto.
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            p.mb-0 <span style="color:#0273BC">#[strong Descripción del producto]</span>: detalles del producto, incluidos elementos como el color, la categoría del producto o el tipo de material del que está hecho.
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            p.mb-0 <span style="color:#0273BC">#[strong Tipo/categoría de producto]</span>: cómo se ha clasificado el producto en función de las ofertas del proveedor.
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            p.mb-0 <span style="color:#0273BC">#[strong Precio]</span>: precio del producto, junto con los posibles descuentos.
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            p.mb-0 <span style="color:#0273BC">#[strong Imágenes]</span>: incluye cualquier foto profesional que tenga del producto.
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            p.mb-0 <span style="color:#0273BC">#[strong Activos promocionales]</span>: además de las imágenes, enumere los activos de marketing, como videos o gráficos, publicaciones de blog, guías y otros recursos que tengan que ver con el producto.
          li
            <i class="fas fa-dot-circle" style="color:#0273BC"></i>
            p.mb-0 <span style="color:#0273BC">#[strong Garantía]</span>: especifique la garantía o cláusulas de garantía del producto y la política de devolución.

    .BGM17.p-4
      .h5.text-center A continuación, se muestra un ejemplo de un producto en un portafolio:
      .row.justify-content-center.mb-4
        .col-md-10
          .titulo-sexto.color-acento-contenido.mb-4(data-aos="fade-right")
            h5 Figura 4
            span Ejemplo producto en portafolio
          figure(data-aos="zoom-in")
            img(src="@/assets/curso/tema7/img03.png")
            figcaption Nota. Tomada de Ortoplus (2020).

</template>

<script>
export default {
  name: 'Tema7',
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
