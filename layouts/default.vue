<template>
  <v-app>
    <div>
      <v-app-bar color="deep-purple accent-4" dark>
        <v-app-bar-nav-icon></v-app-bar-nav-icon>
        <v-toolbar-title>Page title</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-btn icon>
          <v-icon>mdi-heart</v-icon>
        </v-btn>
        <v-btn icon>
          <v-icon>mdi-magnify</v-icon>
        </v-btn>
      </v-app-bar>
    </div>

    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>

    <v-footer fixed app>
      <span>&copy; 2019</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {}
</script>
