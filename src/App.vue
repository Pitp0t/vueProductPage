<template>
  <v-app>
    <Header />
    <RelatedPrductsVue />
    <Chat />
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import Header from "../src/components/Header.vue";
import Chat from "../src/components/Chat.vue";
import RelatedPrductsVue from "./components/RelatedPrducts.vue";
export default {
  name: "App",
  components: {
    Header,
    RelatedPrductsVue,
    Chat,
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
  height: 200vh;
}
</style>
