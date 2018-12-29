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

export default {
  head(){
    return {
      title: 'Meta tags with vuu',
      meta: [
        {
          name: 'og:title',
          content: 'hahahtest'
        },
        {
          name: 'og:image',
          content: 'https://www.google.com/imgres?imgurl=https%3A%2F%2Fcdn1.valuegaia.com.br%2Fgaiasite%2F21219%2Fmedia%2F1365886ce64a6f9dedbe899d94634a94-casa.jpg&imgrefurl=https%3A%2F%2Fwww.carneirolyraimoveis.com.br%2F&docid=JctqvQ6u3uOeOM&tbnid=TuNluZAptdgPqM%3A&vet=10ahUKEwj_udrv38XfAhUEfZAKHf8wC_oQMwg9KAAwAA..i&w=491&h=296&bih=690&biw=1280&q=imovel%20foto&ved=0ahUKEwj_udrv38XfAhUEfZAKHf8wC_oQMwg9KAAwAA&iact=mrc&uact=8'
        },
        {
          name: 'og:description',
          content: 'batatas'
        },
        {
          name: 'keywords',
          keywords: 'fritas'
        },
        {
          hid: `og:title`,
          name: 'og:title',
          content: 'hahahtest'
        },
        {
          hid: `og:image`,
          name: 'og:image',
          content: 'https://www.google.com/imgres?imgurl=https%3A%2F%2Fcdn1.valuegaia.com.br%2Fgaiasite%2F21219%2Fmedia%2F1365886ce64a6f9dedbe899d94634a94-casa.jpg&imgrefurl=https%3A%2F%2Fwww.carneirolyraimoveis.com.br%2F&docid=JctqvQ6u3uOeOM&tbnid=TuNluZAptdgPqM%3A&vet=10ahUKEwj_udrv38XfAhUEfZAKHf8wC_oQMwg9KAAwAA..i&w=491&h=296&bih=690&biw=1280&q=imovel%20foto&ved=0ahUKEwj_udrv38XfAhUEfZAKHf8wC_oQMwg9KAAwAA&iact=mrc&uact=8'
        },
        {
          hid: `og:descriptions`,
          name: 'og:description',
          content: 'batatas'
        },
        {
          hid: `og:keywords`,
          name: 'keywords',
          keywords: 'fritas'
        },
        {
          hid: `title`,
          name: 'title',
          content: 'hahahtest'
        },
        {
          hid: `image`,
          name: 'image',
          content: 'https://www.google.com/imgres?imgurl=https%3A%2F%2Fcdn1.valuegaia.com.br%2Fgaiasite%2F21219%2Fmedia%2F1365886ce64a6f9dedbe899d94634a94-casa.jpg&imgrefurl=https%3A%2F%2Fwww.carneirolyraimoveis.com.br%2F&docid=JctqvQ6u3uOeOM&tbnid=TuNluZAptdgPqM%3A&vet=10ahUKEwj_udrv38XfAhUEfZAKHf8wC_oQMwg9KAAwAA..i&w=491&h=296&bih=690&biw=1280&q=imovel%20foto&ved=0ahUKEwj_udrv38XfAhUEfZAKHf8wC_oQMwg9KAAwAA&iact=mrc&uact=8'
        },
        {
          hid: `descriptions`,
          name: 'description',
          content: 'batatas'
        },
        {
          hid: `keywords`,
          name: 'keywords',
          keywords: 'fritas'
        }
      ]
    }
  },
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
