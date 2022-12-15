<script>
export default {
  name: "Footer",
};
</script>

<template>
  <footer class="footer">
    <v-container class="footer_container">
      <!-- Stack the columns on mobile by making one full-width and the other half-width -->
      <v-row>
        <v-col cols="12" md="4">
          <img src="../assets/logo-foschia-footer.webp" alt="" />
        </v-col>
        <v-col cols="6" md="2">
          <div>
            <a href="">info@foschia.com.ar</a>
            <a href="">(011) 6012-3758</a>
            <h3>Colectora Este 30451, El Talar, Buenos aires</h3>
          </div>
        </v-col>
        <v-col cols="6" md="2">
          <div>
            <h3>INSTITUCIONAL</h3>
            <div class="d-flex flex-column">
              <a href="#">Sobre Foschia</a>
              <a href="#">Sucursales</a>
              <a href="#">Información Legal</a>
            </div>
          </div>
        </v-col>
        <v-col cols="6" md="2">
          <div>
            <h3>SERVICIO AL CLIENTE</h3>
            <div class="d-flex flex-column">
              <a href="#">Políticas de Envío</a>
              <a href="#">Políticas de Cambio</a>
              <a href="#">Cláusulas de Venta</a>
              <a href="#">Métodos de Pago</a>
            </div>
          </div>
        </v-col>
        <v-col cols="6" md="2">
          <div>
            <h3>TUS FAVORITAS</h3>
            <div class="d-flex flex-column">
              <a href="#">Mejores Ofertas</a>
              <a href="#">Hot Sale</a>
              <a href="#">Cyber Monday</a>
            </div>
          </div>
        </v-col>
        <v-col cols="12" md="12"> <v-divider color="white"></v-divider></v-col>
        <v-col cols="12" md="8">
          <h4>
            Copyright © 2020 Construdiseño S.A. El uso de este sitio web implica la aceptación de los Términos y Condiciones y de las Políticas de Privacidad de
            Construdiseño S.A. Las fotos son a modo ilustrativo. La venta de cualquiera de los productos publicados está sujeta a la verificación de stock. Los
            precios online para los productos presentados/publicados en www.foschia.com.ar son válidos exclusivamente para la compra vía internet en las páginas
            antes mencionadas. foschia.com.ar
          </h4>
        </v-col>
        <v-col cols="6" md="4">
          <h3>SELLOS</h3>
          <div class="d-flex">
            <img class="footer_img mr-4" src="../assets/data-fiscal.webp" alt="" />
            <img class="footer_img mr-4" src="../assets/sello-cace.webp" alt="" />
            <img class="footer_img mr-4" src="../assets/datos-personales.webp" alt="" />
          </div>
        </v-col>
        <v-col cols="12" md="12"> <v-divider color="white"></v-divider></v-col>
        <v-col cols="12" md="12">
          <h3 class="drubbit">Diseñado y desarrollado por <a href="">drubbit.com</a></h3>
        </v-col>
      </v-row>
    </v-container>
  </footer>
</template>

<style lang="scss">
.v-application a {
  color: white;
}
a {
  text-decoration: none;
  color: white !important;
}
.footer {
  margin-top: 5em;
  background-color: black;
  .footer_container {
    color: white;
    margin: 0 auto;
    max-width: 1200px;
    h3 {
      font-size: 0.8rem;
    }
  }
}

.drubbit {
  text-align: center;
}

.footer_img {
  height: 50px;
}
</style>
