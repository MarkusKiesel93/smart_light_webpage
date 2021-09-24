<template>
  <v-app>
    <v-main>
      <LightControl />
    </v-main>
  </v-app>
</template>

<script>
import LightControl from './components/LightControl.vue'

export default {
  name: "App",

  components: {
    LightControl,
  },

  data: () => ({
    //
  }),
};
</script>
