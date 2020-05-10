<template>
  <v-row no-gutters class="home-page">
    <v-col
      cols="6"
      offset-md="3"
      offset-sm="2"
    >
    
      <div class="page-header">
        <h1>All Curricula</h1>
        <v-btn>Create New</v-btn>
      </div>

      <div class="curricula-list">
        <v-card 
          outlined
        >
          <v-card-title class="headline">Headline 5</v-card-title>
          <v-card-subtitle>
            this is description.....
          </v-card-subtitle>
        </v-card>
      </div>

    </v-col>
  </v-row>
</template>

<script>
// @ is an alias to /src


export default {
  name: "Home"
};
</script>
