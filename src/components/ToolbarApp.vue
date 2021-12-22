<template>
  <v-app-bar app flat dark>
    <avatar :username="username" />
    <v-spacer />
    <v-app-bar-nav-icon/>
  </v-app-bar>
</template>

<script>
import Avatar from "./Avatar.vue";
export default {
    props: ["username"],
    components: {
        Avatar
    }
};
</script>

<style>
@import 'https://cdn.jsdelivr.net/npm/vuetify/dist/vuetify.min.css';
</style>
