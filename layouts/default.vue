<template>
  <v-app>
    <div>
      <v-app-bar color="deep-purple accent-4" dark>
        <v-toolbar-title>StoryBlok Blog</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-btn text color="white">
          <nuxt-link to="/">All Posts</nuxt-link>
        </v-btn>
        <v-btn text>
          <nuxt-link to="about">About</nuxt-link>
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

<style lang="scss" scoped>
.v-application a {
  color: white;
  text-decoration: none;
}
</style>
