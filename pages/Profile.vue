<template>
  <v-layout row wrap>
    <v-toolbar flat color="transparent">
      <!-- <v-toolbar-side-icon>
        <v-icon>person</v-icon>
      </v-toolbar-side-icon> -->
      <v-toolbar-title>
        <span class="display-2">Profile</span>
      </v-toolbar-title>
      <v-spacer />
      <v-toolbar-items>
        <v-btn flat icon large to="/">
          <v-icon large>home</v-icon>
        </v-btn>
      </v-toolbar-items>
    </v-toolbar>
  </v-layout>
</template>
<script>
export default {
  name: 'Profile',
  layout: 'Contents'
}
</script>
