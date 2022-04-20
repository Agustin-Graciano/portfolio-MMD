<template>
  <v-app-bar app color="#13007e" dark flat class="px-8">
    <v-btn  color="transparent" onClick="window.location.href=window.location.href">
      <v-icon color="grey">fas fa-folder-open</v-icon>
    </v-btn>
    <v-div style="font-weight: lighter" class="white--text">My</v-div> 
    <v-div style="font-weight: normal" class="white--text">Portfolio</v-div> 
    <v-spacer></v-spacer>
     <v-divider class="hidden-xs-only" vertical inset></v-divider>
    <v-btn class="hidden-xs-only" text @click="scroll('home')">Home</v-btn>
     <v-divider class="hidden-xs-only" vertical inset></v-divider>
    <v-btn class="hidden-xs-only" text @click="scroll('skills')">skills</v-btn>
     <v-divider class="hidden-xs-only" vertical inset></v-divider>
    <v-btn class="hidden-xs-only" text @click="scroll('projects')">projects</v-btn>
     <v-divider class="hidden-xs-only" vertical inset></v-divider>
    <v-btn class="hidden-xs-only" text @click="scroll('about')">about</v-btn>
     <v-divider class="hidden-xs-only" vertical inset></v-divider>
  </v-app-bar>
</template>

<script>
export default {
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({behavior: "smooth"});
    },
  },
};
</script>

<style>
</style>