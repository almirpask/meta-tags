<template>
  <v-layout
    column
    justify-center
    align-center>
    <v-flex
      xs12
      sm8
      md6>
      <div class="text-xs-center">
        <logo/>
        <vuetify-logo/>
      </div>
      <v-card>
        <v-card-title class="headline">Welcome to the Vuetify + Nuxt.js template</v-card-title>
        <v-card-text>
          <p>Vuetify is a progressive Material Design component framework for Vue.js. It was designed to empower developers to create amazing applications.</p>
          <p>For more information on Vuetify, check out the <a
            href="https://vuetifyjs.com"
            target="_blank">documentation</a>.</p>
          <p>If you have questions, please join the official <a
            href="https://chat.vuetifyjs.com/"
            target="_blank"
            title="chat">discord</a>.</p>
          <p>Find a bug? Report it on the github <a
            href="https://github.com/vuetifyjs/vuetify/issues"
            target="_blank"
            title="contribute">issue board</a>.</p>
          <p>Thank you for developing with Vuetify and I look forward to bringing more exciting features in the future.</p>
          <div class="text-xs-right">
            <em><small>&mdash; John Leider</small></em>
          </div>
          <hr class="my-3">
          <a
            href="https://nuxtjs.org/"
            target="_blank">Nuxt Documentation</a>
          <br>
          <a
            href="https://github.com/nuxt/nuxt.js"
            target="_blank">Nuxt GitHub</a>
        </v-card-text>
        <v-card-actions>
          <v-spacer/>
          <v-btn
            color="primary"
            flat
            nuxt
            to="/inspire">Continue</v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'
// https://firebasestorage.googleapis.com/v0/b/iasd-news.appspot.com/o/teste.jpg?alt=media&token=03ad9a6e-2a67-4c51-9010-8ca60567b11c
export default {
  head(){
    return {
      title: 'Meta tags with vuu',
      meta: [
        {
          'og:title': 'meta tags test',
          'og:description': 'meta tags test description',
          'og:image': 'https://hangouts.google.com/_/elUi/chat-redirect?authuser=1&dest=https%3A%2F%2Ffirebasestorage.googleapis.com%2Fv0%2Fb%2Fiasd-news.appspot.com%2Fo%2Fteste.jpg%3Falt%3Dmedia%26token%3D03ad9a6e-2a67-4c51-9010-8ca60567b11c',
        },
      ]
    }
  },
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
