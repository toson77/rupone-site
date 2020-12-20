<template>
  <v-container fill-height>
    <v-row justify="center" align="center">
      <v-col cols="12" sm="8" md="6">
        <div class="text-center"></div>
        <v-card>
          <v-card-text>
            <h1>
              VRC is very dark, so be careful... Do you want to look into the
              abyss?
            </h1>
          </v-card-text>
          <v-card-actions>
            <v-spacer />
            <v-btn color="error" nuxt to="/no"> NO </v-btn>
            <v-btn color="primary" nuxt to="/yes"> YES </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
// import Logo from '~/components/Logo.vue'
// import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    /* Logo,
    VuetifyLogo, */
  },
}
</script>

<style>
h1 {
  font-size: 50px;
  line-height: 1.4em;
}
</style>
