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
  <v-row justify="center">
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

        <v-divider></v-divider>
      </v-card>
    </v-dialog>
  </v-row>
</template>
