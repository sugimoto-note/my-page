<template>
  <v-app>
    <v-container fluid fill-height>
      <v-layout justify-start column>
        <v-layout row wrap align-center justify-center>
          <v-flex xs12 sm10 md8 lg6>
            <logo/>
            <h1 class="display-4">Sugimoto Note</h1>
            <h2 class="display-3 font-weight-light">Portfolio</h2>
          </v-flex>
        </v-layout>
        <v-layout row wrap align-start justify-center>
          <v-flex xs12 sm10 md8 lg6>
            <v-layout row wrap align-start justify-space-around>
              <v-flex v-for="item in list" :key="item.id" xs12 sm6 md4 lg3 class="pa-1">
                <v-btn :to="item.link" outline block large color="primary">{{ item.text }}</v-btn>
              </v-flex>
            </v-layout>
          </v-flex>
        </v-layout>
      </v-layout>
    </v-container>
  </v-app>
</template>

<script>
import Logo from '@/components/Logo.vue'

export default {
  components: {
    Logo
  },
  data() {
    return {
      list: [
        {
          link: '/profile',
          text: 'Profile'
        },
        {
          link: '/Skill',
          text: 'Skill'
        },
        {
          link: '/Works',
          text: 'Works'
        },
        {
          link: '/Contact',
          text: 'Contact'
        }
      ]
    }
  }
}
</script>
