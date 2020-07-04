<template>
  <v-app>
    <v-app-bar app flat color="#072f24" dark>
      <div class="d-flex align-center">
        <v-img
          alt="Angry Deer Logo"
          class="shrink mr-2"
          contain
          src=""
          transition="scale-transition"
          width="40"
        />

        <v-img
          alt="Angry Deer Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src=""
          width="100"
        />
      </div>

      <v-spacer></v-spacer>
    </v-app-bar>

    <v-content style="background:#095b46">
      <HelloWorld />
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",

  components: {
    HelloWorld
  },

  data: () => ({})
};
</script>
