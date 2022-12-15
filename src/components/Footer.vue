<script>
export default {
  name: "Footer",
};
</script>

<template>
  <div>
    <v-container class="grey lighten-5">
      <!-- Stack the columns on mobile by making one full-width and the other half-width -->
      <v-row>
        <v-col cols="12" md="8">
          <v-card class="pa-2" outlined tile> .col-12 .col-md-8 </v-card>
        </v-col>
        <v-col cols="6" md="4">
          <v-card class="pa-2" outlined tile> .col-6 .col-md-4 </v-card>
        </v-col>
      </v-row>

      <!-- Columns start at 50% wide on mobile and bump up to 33.3% wide on desktop -->
      <v-row>
        <v-col v-for="n in 3" :key="n" cols="6" md="4">
          <v-card class="pa-2" outlined tile> .col-6 .col-md-4 </v-card>
        </v-col>
      </v-row>

      <!-- Columns are always 50% wide, on mobile and desktop -->
      <v-row>
        <v-col v-for="n in 2" :key="n" cols="6">
          <v-card class="pa-2" outlined tile> .col-6 </v-card>
        </v-col>
      </v-row>
    </v-container>

    <footer class="footer">
      <div class="footer_container">
        <div class="d-flex footer_top flex-column flex-md-row justify-md-center justify-md-space-between">
          <div>
            <img src="../assets/logo-foschia-footer.webp" alt="" />
          </div>
          <div class="d-flex footer_top_info flex-column flex-md-row justify-md-center justify-md-space-between">
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
              Copyright © 2020 Construdiseño S.A. El uso de este sitio web implica la aceptación de los Términos y Condiciones y de las Políticas de Privacidad
              de Construdiseño S.A. Las fotos son a modo ilustrativo. La venta de cualquiera de los productos publicados está sujeta a la verificación de stock.
              Los precios online para los productos presentados/publicados en www.foschia.com.ar son válidos exclusivamente para la compra vía internet en las
              páginas antes mencionadas. foschia.com.ar
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
  </div>
</template>

<style scoped lang="scss">
.footer {
  background-color: black;
  .footer_container {
    padding: 3em 0;
    max-width: 1200px;
    width: 100%;
    color: white;
    margin: 0 auto;
    gap: 50px;
    .footer_top {
      justify-content: space-around;
      border: 3px solid red;
      width: 100%;
      .footer_top_info {
      }
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
