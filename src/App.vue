<template>
  <v-app>
    <Navbar />

    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Navbar from './components/Navbar.vue';

export default {
  name: 'App',

  components: {
    HelloWorld,
    Navbar,
  },

  data: () => ({
    //
  }),
};
</script>
