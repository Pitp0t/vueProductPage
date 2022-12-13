<script>
export default {
  name: "Chat",
  data() {
    return {
      dialog: false,
      notifications: false,
      sound: true,
      widgets: false,
    };
  },
};
</script>

<template>
  <v-row class="space-around">
    <v-dialog v-model="dialog" fullscreen hide-overlay x-large transition="dialog-bottom-transition">
      <template v-slot:activator="{ on, attrs }">
        <v-btn class="chatButton" color="primary" fixed bottom right fab dark v-bind="attrs" v-on="on">
          <v-icon dark> mdi-message-text </v-icon>
        </v-btn>
      </template>
      <v-card>
        <v-toolbar dark color="primary">
          <v-icon dark> mdi-message-text </v-icon>
          <v-spacer></v-spacer>
          <v-btn icon dark @click="dialog = false">
            <v-icon>mdi-close</v-icon>
          </v-btn>
        </v-toolbar>
        <div class="containerFlex">
          <div class="message">
            <v-icon class="msgIcon" color="primary">mdi-message-text</v-icon>
            <div class="bubbleText">
              <h3>Hola!😀 Gracias por contactarte con Foschia. En que podemos ayudarte?</h3>
            </div>
          </div>
        </div>
        <div class="inputGroup">
          <input class="input" type="text" placeholder="EscribÍ acá..." />
          <v-btn> <v-icon>mdi-arrow-up-bold-box-outline</v-icon></v-btn>
        </div>
      </v-card>
    </v-dialog>
  </v-row>
</template>

<style scoped lang="scss">
.containerFlex {
  border-bottom: 2px solid rgba(185, 185, 185, 0.232);
  padding: 3em 2em;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  height: 80vh;
  width: 100%;
  .message {
    display: flex;
    position: relative;
    .msgIcon {
      position: absolute;
      bottom: -30px;
      left: -30px;
    }
    .bubbleText {
      background-color: #f3f3f3;
      padding: 1em;
      border-radius: 1em 1em 1em 0;
    }
  }
}
.inputGroup {
  overflow: hidden;
  display: flex;
  .input {
    padding: 0 1em;
    outline: none;
    flex-basis: calc(100% - 30px);
  }
}
</style>
