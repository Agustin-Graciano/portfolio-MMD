<template>
  <v-footer dark padless>
    <v-card
      flat
      tile
      class="white--text py-5 px-5 text-center" color="#13007e"
      width="100%"
    >
      <v-row>
        <v-col cols="12" sm="4">
          <v-card-text class="white--text pt-2">
               <v-btn  color="transparent" onClick="window.location.href=window.location.href">
              <v-icon color="grey">fas fa-folder-open</v-icon>
            </v-btn>
            <v-div style="font-weight: lighter" class="white--text">My</v-div> 
              <v-div style="font-weight: normal" class="white--text">Portfolio</v-div> 
          </v-card-text> 
        </v-col>
        
        <v-row>
        <v-col cols="12" sm="6">
           <v-card-text class="grey--text text--lighten-2">
               <v-btn icon href="https://www.linkedin.com/" target="_blank">
              <v-icon x-medium class="mt-5 ml-3">mdi-linkedin</v-icon>
             </v-btn>
             <v-btn icon href="https://github.com/Agustin-Graciano" target="_blank">
              <v-icon x-medium class="mt-5 ml-3">mdi-github</v-icon>
             </v-btn>
             <h4 class="mt-2"> <span>@</span> Vuetify Agustin Graciano 2022 <span>@</span> </h4>
          </v-card-text> 
         </v-col>

         </v-row>
       </v-row>
    </v-card>
  </v-footer>
</template>

<script>
export default {};
</script>

<style>
span{
 color:rgb(158, 158, 195);
}
</style>

