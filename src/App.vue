<template>
  <div>
  <v-app>
  <v-container fluid>
    <v-row>
      <v-col class=" col-md-2 deep-orange lighten-5"><SideBar></SideBar></v-col>
      <v-col class="col-md-4 "><TodayPlan></TodayPlan></v-col>
      <v-col class="col-md-5 deep-orange lighten-5"><MonthlyPinned></MonthlyPinned></v-col>
      <v-col  class="col-md-1 deep-orange lighten-5"><UserProfile></UserProfile></v-col>
    </v-row>
    
  </v-container></v-app></div>
 
</template>

<script>
import SideBar from './components/SideBar';
import TodayPlan from './components/TodayPlan';
import MonthlyPinned from './components/MonthlyPinned';
import UserProfile from './components/UserProfile';


export default {
  name: 'App',

  components: {
    SideBar,
    TodayPlan,
    UserProfile,
    MonthlyPinned,
  },

  data: () => ({
    //
  }),
};
</script>
