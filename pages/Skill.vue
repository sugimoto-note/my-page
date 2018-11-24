<template>
  <v-layout row wrap>
    <v-toolbar flat color="transparent">
      <!-- <v-toolbar-side-icon>
        <v-icon>person</v-icon>
      </v-toolbar-side-icon> -->
      <v-toolbar-title>
        <span class="display-2">Skill</span>
      </v-toolbar-title>
      <v-spacer />
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn flat to="/">HOME</v-btn>
      </v-toolbar-items>
    </v-toolbar>
  </v-layout>
</template>
<script>
export default {
  name: 'Skill',
  layout: 'Contents'
}
</script>
