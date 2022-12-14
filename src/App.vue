<template>
  <v-app>
    <Header />
    <ProductInfo />
    <RelatedPrductsVue />
    <Chat />
    <Footer />
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import Header from "../src/components/Header.vue";
import ProductInfo from "../src/components/ProductInfo.vue";
import RelatedPrductsVue from "./components/RelatedPrducts.vue";
import Footer from "./components/Footer.vue";
import Chat from "../src/components/Chat.vue";

export default {
  name: "App",
  components: {
    Header,
    RelatedPrductsVue,
    Chat,
    Footer,
    ProductInfo,
  },
};
</script>

<style lang="scss">
@font-face {
  font-family: nova;
  src: url("./assets/fonts/novaLigth.otf");
}

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: nova;
  font-weight: lighter;
  font-size: 0.8rem;
}

#app {
  background-color: #e4e4e4;
}
</style>
