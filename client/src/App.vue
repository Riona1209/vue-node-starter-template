<template>
  <v-app>
    <Header v-if="$route.meta.showNavbar" />
    <router-view />
  </v-app>
</template>

<script>
import Header from "./views/CommonViews/CommonComponents/Header.vue";
export default {
  name: "App",
  components: { Header },
};
</script>
