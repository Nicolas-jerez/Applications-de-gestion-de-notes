<template>
  <v-app>
    <HomeContainer/>
  </v-app>
</template>

<script>
import HomeContainer from './components/HomeContainer.vue'

export default {
  name: 'App',

  components: {
    HomeContainer,
  },

  data: () => ({
    //
  }),
}
</script>
