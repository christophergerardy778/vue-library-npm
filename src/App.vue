<template>
  <v-app>
    <toolbar-app />
    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import ToolbarApp from './components/ToolbarApp.vue';

export default {
  name: 'App',

  components: {
    HelloWorld,
    ToolbarApp,
  },

  data: () => ({
    //
  }),
};
</script>
