<template>
    <div class="d-flex flex-column mt-4">
        <div class="d-flex align-center justify-space-between">
            <div class="d-flex flex-column">
             <h2>Today's Plan</h2>
             <p class="grey--text">June 14th, 2022</p>
            </div>
            <v-btn
            fab
            dark
            small
      color="black"
    >
      <v-icon dark>
        mdi-plus
      </v-icon>
    </v-btn>
        </div>
        <div class=" mt-4">
            <p class="text-h6 font-weight-bold">Lorem ipsum dolor sit amet cons  elit conse ctetur adipisicing elit.</p>
        </div>
        <div class="d-flex  justify-space-between">
            <div>
            <v-avatar
            class="avatar"
  size="35"
> <v-img src="https://cdn.vuetifyjs.com/images/lists/2.jpg"></v-img></v-avatar>

<v-avatar
class="avatar"
  size="35"
> <v-img src="https://cdn.vuetifyjs.com/images/lists/2.jpg"></v-img></v-avatar><v-avatar
class="avatar"
  size="35"
> <v-img src="https://cdn.vuetifyjs.com/images/lists/2.jpg"></v-img></v-avatar><v-avatar class="avatar"
  size="35"
> <v-img src="https://cdn.vuetifyjs.com/images/lists/2.jpg"></v-img></v-avatar>
</div>

<div class="d-flex" >
    <v-divider class="ma-0"
      inset
      vertical
    ></v-divider>
    <div class="d-flex flex-column ml-8">
    <h4>Medi Team meeting</h4>
    <p>13:30-14:50</p></div>
</div>
        </div>
        <div>
            <v-card
            elevation="0"
            
    class="mb-4"
    
  >
    <v-img
      src="https://images.unsplash.com/photo-1614850523060-8da1d56ae167?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"
      height="200px"
    ><div class="ma-5 d-flex flex-column">
        <div>
<h3>Weekly Report</h3>
<p>Track Your Perfomance</p>
<v-btn 
      class="rounded-0 mt-10"
      outlined
      
      color="black"
    >
      View Report
    </v-btn>
</div>

</div>
</v-img>
</v-card>
<v-row>
    <v-col class="col-6"> <v-card
            elevation="0"
    class=""
    
  >
    <v-img
      src="https://images.unsplash.com/photo-1614850523060-8da1d56ae167?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"
      height="250px"
    ><div class="ma-5 d-flex flex-column">
        <div>
<h3>Weekly Report</h3>
<p><v-icon class="mr-2">mdi-school</v-icon>Track Your Perfomance</p>

</div>

</div>
</v-img>
  </v-card></v-col>
  <v-col class="col-6"><v-card
            elevation="0"
    class=""
    
  >
    <v-img
      src="https://images.unsplash.com/photo-1614850523060-8da1d56ae167?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"
      height="250px"
    ><div class="ma-5 d-flex flex-column">
        <div>
<h3>
    Weekly Report</h3>
<p><v-icon class="mr-2">mdi-school</v-icon>Track Your Perfomance</p>

</div>

</div>
</v-img>
  </v-card></v-col>
   
</v-row>
        </div>
        
    </div>
</template>
<script>
  export default {
    name: 'TodayPlan',

   
  }
</script>
<style scoped>
.avatar{
    margin-right: -15px;
}
</style>