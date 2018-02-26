<template lang="pug">
v-layout(column='' justify-center='' align-center='')
  v-flex(xs12='' sm8='' md6='')
    .text-xs-center
      Logo
      Vuetify-logo
    v-card
      v-card-title.headline Welcome to the Vuetify + Nuxt.js template
      v-card-text
        p Vuetify is a progressive Material Design component framework for Vue.js. It was designed to empower developers to create amazing applications.      
        hr.my-3
        a(href='https://nuxtjs.org/' target='_blank') Nuxt Documentation
        br
        a(href='https://github.com/nuxt/nuxt.js' target='_blank') Nuxt GitHub
      v-card-actions
        v-spacer
        v-btn(color='primary' flat='' nuxt='' to='/inspire') Continue
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
