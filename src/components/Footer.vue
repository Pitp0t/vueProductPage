<script>
export default {
  name: "Footer",
};
</script>

<template>
  <footer class="footer">
    <div class="footer_container">
      <div class="d-flex footer_top">
        <div>
          <img src="../assets/logo-foschia-footer.webp" alt="" />
        </div>
        <div class="d-flex footer_top">
          <div>
            <a href="">info@foschia.com.ar</a>
            <a href="">(011) 6012-3758</a>
            <h3>Colectora Este 30451, El Talar, Buenos aires</h3>
          </div>
          <div class="d-flex flex-column">
            <h3>INSTITUCIONAL</h3>
            <a href="#">Sobre Foschia</a>
            <a href="#">Sucursales</a>
            <a href="#">Información Legal</a>
          </div>
          <div class="d-flex">
            <div class="d-flex flex-column">
              <h3>SERVICIO AL CLIENTE</h3>
              <a href="#">Políticas de Envío</a>
              <a href="#">Políticas de Cambio</a>
              <a href="#">Cláusulas de Venta</a>
              <a href="#">Métodos de Pago</a>
            </div>
            <div class="d-flex flex-column">
              <h3>TUS FAVORITAS</h3>
              <a href="#">Mejores Ofertas</a>
              <a href="#">Hot Sale</a>
              <a href="#">Cyber Monday</a>
            </div>
          </div>
        </div>
      </div>
      <div class="d-flex">
        <div>
          <h4>
            Copyright © 2020 Construdiseño S.A. El uso de este sitio web implica la aceptación de los Términos y Condiciones y de las Políticas de Privacidad de
            Construdiseño S.A. Las fotos son a modo ilustrativo. La venta de cualquiera de los productos publicados está sujeta a la verificación de stock. Los
            precios online para los productos presentados/publicados en www.foschia.com.ar son válidos exclusivamente para la compra vía internet en las páginas
            antes mencionadas. foschia.com.ar
          </h4>
        </div>
        <div>
          <h3>SELLOS</h3>
          <div class="d-flex footer_imgContainer">
            <img class="footer_img" src="../assets/data-fiscal.webp" alt="" />
            <img class="footer_img" src="../assets/sello-cace.webp" alt="" />
            <img class="footer_img" src="../assets/datos-personales.webp" alt="" />
          </div>
        </div>
      </div>
      <div>
        <h3>Diseñado y desarrollado por <a href="">drubbit.com</a></h3>
      </div>
    </div>
  </footer>
</template>

<style lang="scss">
.footer {
  background-color: black;
  .footer_container {
    padding: 3em 0;
    max-width: 1200px;
    width: 100%;
    color: white;
    margin: 0 auto;
    display: flex;
    align-items: center;
    flex-direction: column;
    gap: 50px;
    .footer_top {
      width: 100%;
      justify-content: space-around;
    }
  }
}
a {
  text-decoration: none;
  color: white;
}
.footer_imgContainer {
  gap: 10px;
  .footer_img {
    height: 50px;
  }
}
</style>
