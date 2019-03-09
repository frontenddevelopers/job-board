<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Job board</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn flat href="https://frontenddevelopers.org/" target="_blank">
        <span class="mr-2">frontenddevelopers.org</span>
      </v-btn>
    </v-toolbar>

    <v-content>
      <HelloWorld />
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data() {
    return {
      //
    }
  }
}
</script>
