<template>
  <v-row>
    <v-col>
      sdsd
    </v-col>
  </v-row>
</template>

<script>
export default {
  components: {},
  asyncData(context) {
    return context.app.$storyapi
      .get('cdn/stories', {
        version: 'draft',
        starts_with: 'blog/'
      })
      .then((res) => {
        console.log(res.data)
        return res.data
      })
  }
}
</script>
