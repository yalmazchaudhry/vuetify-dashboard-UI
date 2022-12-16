<template>
  <div class="d-flex flex-column justify-space-between">
 <div class="d-flex flex-column  align-center mt-4">
  <v-icon  large color="black darken-2">mdi-anchor</v-icon>
<h1>SOLARIUS</h1>
</div>
<div>
  <v-list class="deep-orange lighten-5">
      <v-list-item>
        <v-list-item-icon>
          <v-icon color="black darken-2">mdi-view-dashboard</v-icon>
        </v-list-item-icon>

        <v-list-item-title class="font-weight-black">Dashboard</v-list-item-title>
      </v-list-item>
      <v-list-item>
        <v-list-item-icon>
          <v-icon color="black darken-2">mdi-school</v-icon>
        </v-list-item-icon>

        <v-list-item-title class="font-weight-black">Education</v-list-item-title>
      </v-list-item>

      <v-list-group
        :value="true">
        <template  v-slot:activator>
          <v-list-item-icon>
          <v-icon color="black">mdi-school</v-icon>
        </v-list-item-icon>
          <v-list-item-title class="font-weight-black" color="black">
            Resources</v-list-item-title>
        </template>
        <v-list-item class="ml-4">
        <v-list-item-icon>
          <v-icon color="pink lighten-4">mdi-square-rounded</v-icon>
        </v-list-item-icon>

        <v-list-item-title>Education</v-list-item-title>
      </v-list-item>
      <v-list-item class="ml-4">
        <v-list-item-icon>
          <v-icon color="deep-orange lighten-4">mdi-square-rounded</v-icon>
        </v-list-item-icon>

        <v-list-item-title>Education</v-list-item-title>
      </v-list-item>
      <v-list-item class="ml-4">
        <v-list-item-icon>
          <v-icon color="blue-grey ">mdi-square-rounded</v-icon>
        </v-list-item-icon>

        <v-list-item-title>Education</v-list-item-title>
      </v-list-item>
        
      </v-list-group>
      <v-list-item>
        <v-list-item-icon>
          <v-icon color="black darken-2">mdi-cog-outline</v-icon>
        </v-list-item-icon>

        <v-list-item-title class="font-weight-black">Settings</v-list-item-title>
      </v-list-item>
    </v-list>
</div>
<div class="d-flex align-center">
  <v-btn
      fab
      dark
      x-small
      color="black"
    >
      <v-icon dark>
        mdi-logout
      </v-icon>
    </v-btn>
    <p class="ml-2 pt-4  font-weight-black">Log out</p>
</div>
</div>
</template>

<script>
  export default {
    name: 'SideBar',

   
  }
</script>
