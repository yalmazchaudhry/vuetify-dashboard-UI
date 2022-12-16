<template>
    
    <div class="d-flex align-center justify-space-between flex-column mt-4">
        <div class="d-flex align-center flex-column mb-15 pb-15">
            <v-badge
        bordered
        top
        color="green accent-4"
        dot
        offset-x="10"
        offset-y="10"
      >
        <v-avatar size="50">
          <v-img src="https://cdn.vuetifyjs.com/images/lists/2.jpg"></v-img>
        </v-avatar>
      </v-badge>
      <p class=" font-weight-bold ma-0 pt-2">Dr. Edward</p>
             <p class="grey--text text-caption">Scientist</p>
        </div>
        <div class="mb-15"></div>
        <div class="mb-15"></div>
        <div class="mb-15"></div>
        <div class="mt-15">
            <v-speed-dial class="mt-15"
      v-model="fab"
      :top="top"
      :bottom="bottom"
      :right="right"
      :left="left"
      :direction="direction"
      :open-on-hover="hover"
      :transition="transition"
    >
      <template v-slot:activator>
        <v-btn
          v-model="fab"
          color="black"
          dark
          fab
        >
          <v-icon v-if="fab">
            mdi-close
          </v-icon>
          <v-icon v-else>
            mdi-plus
          </v-icon>
        </v-btn>
      </template>
      <v-btn
        fab
        dark
        small
        color="white"
      >
        <v-icon color="black">mdi-pencil</v-icon>
      </v-btn>
      <v-btn
        fab
        dark
        small
        color="white"
      >
        <v-icon color="black">mdi-plus</v-icon>
      </v-btn>
      
    </v-speed-dial>
        </div>
    </div>
</template>
<script>
export default{
    name: 'UserProfile',
    data: () => ({
      direction: 'top',
      fab: false,
      fling: false,
      hover: false,
      tabs: null,
      top: false,
      right: true,
      bottom: true,
      left: false,
      transition: 'slide-y-reverse-transition',
    }),

    watch: {
      top (val) {
        this.bottom = !val
      },
      right (val) {
        this.left = !val
      },
      bottom (val) {
        this.top = !val
      },
      left (val) {
        this.right = !val
      },
    },
}
</script>
<style>

</style>