<template>
  <v-app>
    <Header />
    <Chat />
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import Header from "../src/components/Header.vue";
import Chat from "../src/components/Chat.vue";
export default {
  name: "App",
  components: {
    Header,
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
  font-size: 16px;
}

#app {
  height: 200vh;
}
</style>
