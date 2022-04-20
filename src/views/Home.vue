<template>
  <v-app id="home" :style="{ background: $vuetify.theme.themes.dark.background }">
    <nav-bar/>
    <v-container fluid>
      <v-row> 
        <v-col cols="6" lg="6" md="12" sm="12" offset-xs-only="3" xs="12" justify="center">
          <v-img src="Portfolio Art.png" contain max-height="500" class="mt-4 mr-4 ml-4"></v-img>
        </v-col>

        <v-col cols="6" lg="6" offset-md-only="3" md="8" sm="12" offset-xs-only="3" xs="12">
          <h1 class="white--text mb-2 mt-15 ml-10 mr-10 offset-sm-2" contain max-height="500">IM A MULTIMEDIA DESIGNER!</h1>
          <h3 class="subheading grey--text text--lighten-2 ml-10 mt-2 mb-6 offset-sm-2">
            Do you need a hand being creative in your business or maybe:</h3>
            <p class="grey--text text--lighten-2 ml-10 mt-6 mb-6 offset-sm-2">
                   <span>@</span> A website to promote your business. 
            <br /> <span>@</span> Any kind of infographic material or design.
            <br /> <span>@</span> Video editing.
            <br /> <span>@</span> 3D Modelling and Animation. </p> 
            <h3 class="subheading grey--text text--lighten-2 ml-10 mt-0 mb-6 offset-sm-2">I can help you with that! <span> ==> </span>
            <v-btn href="mailto:agusnachogracianox@gmail.com" tile color="#13007e" dark class="mr-1 ml-1"> CONTACT ME! </v-btn> </h3>
         </v-col>

        <v-col cols="12" sm="12" class="padd hidden-xs-only">
          <div class="first" id="skills">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="grey" x-large class="ml-3"
                    >mdi-palette-swatch</v-icon>
                  <h3 class="white--text ml-3 mt-2">UI/UX Design</h3>
                  <p class="grey--text text--lighten-2 ml-3 mt-2">
                    Prototype and concept idea, <br />before real implementation.</p>
                  <v-img src="Adobe Logo UX.png" aspect-ratio="3.7" height="44px" width="45px"></v-img>
                </div>

                <div class="child bgColor2">
                  <v-icon color="grey" x-large class="ml-3">photograph</v-icon>
                  <h3 class="white--text ml-3 mt-2">Graphic Design</h3>
                  <p class="grey--text text--lighten-2 ml-3 mt-2"> Careful and tailored design
                   <br />in order to be implemented<br />into your project.</p>
                 <v-img src="Adobe Logos gd.png" aspect-ratio="3.7" height="47px" width="176px"></v-img>
                </div>
                
                <div class="child bgColor1">
                  <v-icon color="grey" x-large class="ml-3"
                    >mdi-camera</v-icon>
                  <h3 class="white--text ml-3 mt-2">Video/Audio Editing</h3>
                  <p class="grey--text text--lighten-2 ml-3 mt-2">
                    Video and audio editing,<br /> 3D animation and modelling.</p>
                  <v-img src="Adobe Logos Video Editing.png" aspect-ratio="3.7" height="46px" width="176px"></v-img>
                  
               </div>
              </v-col>
              <v-col cols="12 hidden-sm-only hidden-xs-only" class="mRigth">
                <div class="child1">
                  <h1 class="bgColor2 grey--text number pt-0 pb-0 pl-3 pr-3 mr-6 ml-6">3</h1>
                  <h3 class="bgColor2 white--text pt-0 pb-2 pl-3 pr-3 mr-6 ml-6">Programming Languages</h3>
                </div>
                
                  <div class="child2 mr-2">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="white--text text--lighten-2">HTML</h1>
                    </div>

                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="white--text text--lighten-2">CSS</h1>
                      </div>
                    </v-col>
                  </v-row>
                </div>
                
                <div class="child2">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="white--text text--lighten-2">Javascript</h1>
                      </div>
                    </v-col>
                    </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>

        <v-col md="3" offset-md="3" sm="7" offset-sm="3" id="projects">
          <v-btn color="white" dark text class="ml-0" href="https://www.youtube.com/watch?v=k3BqK6jciF8" target="_blank"> Video CV </v-btn>
          <v-card class="pa-6" outlined tile height="200px" color="#13007e">
          <video-embed src="https://www.youtube.com/watch?v=k3BqK6jciF8"></video-embed>
          </v-card>
        </v-col>
        
        <v-col md="3" offset-md="0" sm="7" offset-sm="3">
          <v-btn color="white" dark text class="ml-0" href="https://www.youtube.com/watch?v=6KmrV0w79qw" target="_blank"> Mercedes Commercial </v-btn>
          <v-card class="pa-6" outlined tile height="200px" color="#13007e">
            <video-embed src="https://www.youtube.com/watch?v=6KmrV0w79qw"></video-embed>
          </v-card>
        </v-col>

        <v-col md="3" offset-md="3" sm="7" offset-sm="3">
          <v-btn color="white" dark text class="ml-0"> Content Creation </v-btn>
          <v-card class="pa-6" outlined tile height="200px" color="#13007e">
            <video-embed src="https://www.youtube.com/watch?v=VX1Dl5TdkMs"></video-embed>
          </v-card>
        </v-col>

        <v-col md="3" offset-md="0" sm="7" offset-sm="3">
           <v-btn color="white" dark text class="ml-0" href="https://trapholt.netlify.app/" target="_blank"> Trapholt Website </v-btn>
          <v-card class="pa-6" outlined tile height="200px" color="#13007e">
            <v-img src="Trapholt Website.png" href="https://trapholt.netlify.app/"></v-img>
          </v-card>
        </v-col>
      
       <v-col cols="12" sm="12" sm-width="6" class="padd">
          <div class="second">
            <div class="secondchild1" id="about">
              <v-row>
                <v-col cols="12">
                  <h1 class="white--text hidden-sm-only hidden-xs-only">
                    Hi, my name is Agustin!</h1>
                  <h3 class="grey--text text--lighten-2 hidden-sm-only hidden-xs-only">
                    This is my portfolio project in which i show my skills as a Multimedia Designer student!
                    <br />Being a Multimedia Designer student means im able to help you with:<br />
                    <br /><span>@</span> Creating a website to promote your business / Creative project / Idea.
                    <br /><span>@</span> Creating diverse kind of infographic materials and designs like logos / posters / etc.
                    <br /><span>@</span> Video and audio editing.
                    <br /><span>@</span> 3D modelling and animation (Depending on difficulty and level of model and textures).
                    <br />
                  </h3>
                  <h2 class="white--text">
                      <br /> Dont forget to contact me through Email for any project inquiry! <span> ==> </span> <v-btn href="mailto:agusnachogracianox@gmail.com" tile color="#13007e" dark class="mb-1"> Write an email! </v-btn>
                      <br /> You can also download my CV for any job offer! <span> ==> </span> <v-btn tile color="#13007e" dark class="mb-1" href="CV Agustin Graciano MMD.pdf" download> Download CV </v-btn>
                      </h2>
                </v-col>
              </v-row>
            </div>
          </div>

        </v-col>
      </v-row>
    </v-container>
    <Footer />
  </v-app>
</template>

<script>
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";
import Vue from 'vue'
import Embed from 'v-video-embed'
import pdf from 'vue-pdf'

// global register
Vue.use(Embed);
Vue.use(pdf);

export default { 
  components: {
    NavBar,
    Footer,
  },
};
</script>
<style scoped>

span{
 color:rgb(158, 158, 195);
}

.top {
  margin-top: 180px;
}
.topInverse {
  margin-top: -250px;
}
.topTolbar {
  margin-top: 100px;
  text-align: center;
}
.first {
  width: 100%;
  height: 610px;
  background: linear-gradient(
    #13007e,
    #00005b 20%,
    #000000 100%,
    #000000 100%
  );
  text-align: center;
  padding: 4rem 2rem;
}
.second {
  width: 100%;
  height: 610px;
  background: linear-gradient(
    #13007e,
    #00005b 20%,
    #000000 100%,
    #000000 100%
  );
  text-align: center;
  padding: 4rem 2rem;
}
.secondchild1 {
  display: inline-block;
  background-color: rgb(19, 0, 126);
  padding: 2rem 2rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 20px;
  margin-left: 150px;
  margin-right: 150px;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}
.bgColor1 {
  background-color: #09003f;
}
.bgColor2 {
  background-color: #13007e;
}

.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}
.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}
.mRight {
  margin-right: 8px;
}
.mButton {
  margin-bottom: 8px;
}
.padding {
  padding: 5px 0;
}
.col-12.padd {
  padding: 25px 0 !important;
}
.col-12.childcol {
  padding: 0px !important;
}
h1.number {
  font-size: 50px;
  font-weight: bold;
}
</style>