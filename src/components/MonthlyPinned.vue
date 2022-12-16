<template>
    <div class="d-flex flex-column px-10 mt-4 uyt">
        <div class="d-flex justify-space-between mx-4">
            <h2>Monthly pinned</h2>
             <v-btn
            plain
            dark
            color="black">
            View All
            </v-btn>
        </div>
        <div class="mx-4 ">
            <v-card class="mb-2 "
            outlined>
    <v-list-item three-line class="deep-orange lighten-5">
      <v-list-item-content>
        <div class="grey--text justify-space-between d-flex">
          <p class="">Next-gen-immuno</p><p>5d</p>
        </div>
        
        <v-list-item-title class="text-10 font-weight-black ">
          Mutispecific liquid analysis
        </v-list-item-title>
      </v-list-item-content>

     
    </v-list-item>

    <v-card-actions class="deep-orange lighten-5">
      <v-btn
        plain
        rounded
        
        class="black--text text-caption font-weight-black"
      >
      <v-chip color="red" class="mx-2 " x-small >6</v-chip>
        New Feedback
      </v-btn>
    </v-card-actions>
  </v-card>
  <v-card class="mb-2"
            outlined>
    <v-list-item three-line class="deep-orange lighten-5">
      <v-list-item-content>
        <div class="grey--text justify-space-between d-flex ">
          <p>Next-gen-immuno</p><p>5d</p>
        </div>
        
        <v-list-item-title class="text-10 font-weight-black ">
          Mutispecific liquid analysis
        </v-list-item-title>
      </v-list-item-content>

     
    </v-list-item>

    <v-card-actions class="deep-orange lighten-5">
      <v-btn
        plain
        rounded
        class="black--text text-caption font-weight-black"
      >
      <v-chip color="red" class="mx-2" x-small >6</v-chip>
        New Feedback
      </v-btn>
    </v-card-actions>
  </v-card>
  <v-card class="mb-2"
            outlined>
    <v-list-item three-line class="deep-orange lighten-5">
      <v-list-item-content class="">
        <div class="grey--text justify-space-between d-flex">
          <p >Next-gen-immuno</p><p>5d</p>
        </div>
        
        <v-list-item-title class="text-10 font-weight-black">
          Mutispecific liquid analysis
        </v-list-item-title>
      </v-list-item-content>
 </v-list-item>

    <v-card-actions class="deep-orange lighten-5">
      <v-btn
        plain
        rounded
        class="black--text text-caption font-weight-black"
      >
      <v-chip color="red" class="mx-2" x-small >6</v-chip>
        New Feedback
      </v-btn>
    </v-card-actions>
  </v-card>
        </div>
        <div class="mx-4">
            <div class="d-flex justify-space-between">
            <div class="d-flex flex-column">
             <p class="font-weight-black text-subtitle-1 ma-0">My Learnings</p>
             <p class="grey--text text-caption">Your Progress of medical lectures</p>
            </div>
            <v-btn
            plain
            
            >
      <v-icon >
        mdi-dots-horizontal
      </v-icon>
    </v-btn>
        </div>
        <div class="d-flex flex-wrap justify-space-between  align-content-space-between">
            <div class="d-flex align-center  mt-2">
                <div>
                    <v-avatar
      tile
      size="50"
      color="deep-orange lighten-4"
      class="mb-3"
    >
      <v-icon dark size="20">
        mdi-alarm
      </v-icon>
    </v-avatar>
                </div>
                <div class="d-flex flex-column ml-4">
                    <p class=" font-weight-bold ma-0">Viruses</p>
             <p class="grey--text text-caption">96% progress</p>
                </div>
            </div>
            <div class="d-flex align-center mt-2">
                <div>
                    <v-avatar
      tile
      size="50"
      color="blue lighten-3"
      class="mb-3"
    >
      <v-icon dark size="20">
        mdi-file-settings
      </v-icon>
    </v-avatar>
                </div>
                <div class="d-flex flex-column ml-4 ">
                    <p class=" font-weight-bold ma-0">Viruses</p>
             <p class="grey--text text-caption">96% progress</p>
                </div>
            </div>
            <div class="d-flex align-center mt-2">
                <div>
                    <v-avatar
      tile
      size="50"
      color="orange lighten-4"
      class="mb-3"
    >
      <v-icon dark size="20">
        mdi-credit-card-settings
      </v-icon>
    </v-avatar>
                </div>
                <div class="d-flex flex-column ml-4 ">
                    <p class=" font-weight-bold ma-0">Viruses</p>
             <p class="grey--text text-caption">96% progress</p>
                </div>
            </div>
            
            <div class="d-flex align-center mt-2">
                <div>
                    <v-avatar
      tile
      size="50"
      color="pink lighten-4"
      class="mb-3"
    >
      <v-icon dark size="20">
        mdi-video-input-svideo
      </v-icon>
    </v-avatar>
                </div>
                <div class="d-flex flex-column ml-4 ">
                    <p class=" font-weight-bold ma-0">Viruses</p>
             <p class="grey--text text-caption">96% progress</p>
                </div>
            </div>
        </div>
        
        </div>
        
    </div>
</template>
<script>
export default{
    name: 'MonthlyPinned',
}
</script>
<style>
.uyt{
    border-right: 1px solid #CCCCCC;
}
</style>