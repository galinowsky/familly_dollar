<template>
  <nav>
    <v-app-bar app max-height="60" tile>
      <v-main>
        <v-toolbar-title class="text-uppercase gret--text">
          <span>Familly</span>
          <span class="font-weight-light">Dollar</span>
        </v-toolbar-title>
        <p class="caption">multi-vendor scorecard</p>
      </v-main>
      <v-spacer></v-spacer>
      <v-btn text class="pa-2" to="/">Scorecard</v-btn>
      <v-btn text class="pa-2" to="/data">DataView</v-btn>
      <v-spacer></v-spacer>
      <v-img
        class="pa-2"
        max-height="48"
        max-width="48"
        alt="Vue logo"
        laxy-src="./assets/logo.png"
        src="../assets/logo.png"
      ></v-img>
    </v-app-bar>
  </nav>
</template>

<script>
// import TaskTitle from "./TaskTitle"
export default {
  name: "Navbar",
  components: {
    // TaskTitle
  },
};
</script>