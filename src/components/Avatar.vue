<template>
  <div class="avatar ma-1 pl-5">
    <span class="white--text body-2">Welcome</span>
    <p class="white--text subtitle-2 d-block mb-0">{{ username }}</p>
  </div>
</template>

<script>
export default {
    props: ["username"]
};
</script>

<style>
@import 'https://cdn.jsdelivr.net/npm/vuetify/dist/vuetify.min.css';
</style>
