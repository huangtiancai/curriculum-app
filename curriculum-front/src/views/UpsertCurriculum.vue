<template>
  <v-row no-gutters class="upsert-curricula-page">
    <v-col
      cols="6"
      offset-md="3"
      offset-sm="2"
    >
    
      <div class="page-header">
        <h1>Create Curricula</h1>
        <v-btn>Save</v-btn>
      </div>

      <v-form class="upsert-form">
        <v-row>
          <v-col cols="3">
            <v-subheader  >Name</v-subheader>
          </v-col>
          <v-col cols="9">
            <v-text-field />
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="3">
            <v-subheader>Goal</v-subheader>
          </v-col>
          <v-col cols="9">
            <v-text-field />
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="12">
            <v-label>Description</v-label>
            <v-textarea
              solo
              name="description"
            />
          </v-col>
        </v-row>
      </v-form>

    </v-col>
  </v-row>
</template>