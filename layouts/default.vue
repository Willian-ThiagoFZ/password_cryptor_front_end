<template>
  <v-app dark>
    <v-app-bar
      fixed
      app
      class="text-center"
    >
     <v-toolbar-title> PASSWORD CRYPTOR</v-toolbar-title>
    <v-spacer></v-spacer>

    </v-app-bar>
    <v-main>
      <Nuxt />
    </v-main>
    <v-footer app >
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data () {
    return {
    }
  }
}
</script>
