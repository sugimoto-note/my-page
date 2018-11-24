<template>
  <v-app>
    <v-content>
      <v-container>
        <nuxt/>
      </v-container>
    </v-content>
  </v-app>
</template>
<script>
export default {
  name: 'Contents',
  props: {
    pages: {
      type: String,
      default: ''
    }
  }
}
</script>
