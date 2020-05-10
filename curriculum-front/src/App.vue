<template>
  <v-app id="app">
    <TopNav />
    <v-content>
      <v-container>
        <router-view/>
      </v-container>
    </v-content> 
  </v-app>
</template>

<script>
// @ is an alias to /src
import TopNav from "./components/TopNav.vue";

export default {
  name: "Home",
  components:{
    TopNav
  }
};
</script>
