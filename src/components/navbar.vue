<template>
<div>

   <v-app-bar color="black" dense dark>
     <v-layout column row  pa-5 >
       <v-toolbar-title class="text-sm-h4" >Gracias por visitar mi pagina </v-toolbar-title>
     </v-layout>
        
        <v-spacer></v-spacer>
        <a href="https://www.linkedin.com/in/redwand-jeld-a87564135/" target="_blank" class="black--text">
        <v-btn icon color="blue">
          <v-icon>mdi-linkedin</v-icon>
        </v-btn></a>
        <a href="https://github.com/Redwand-Jeld" target="_blank" rel="noopener noreferrer" class="black--text">
        <v-btn icon color="pink">
          <v-icon>mdi-github</v-icon>
        </v-btn></a>

        <a href="https://www.instagram.com/redou.jeld/" target="_blank" rel="noopener noreferrer" class="black--text">
        <v-btn icon>
          <v-icon>mdi-instagram</v-icon>
        </v-btn>
        </a>

        <a href="https://github.com/Redwand-Jeld/vue-redwand-cv" target="_blank" rel="noopener noreferrer" class="black--text">
        <v-btn icon color="yellow">
          <v-icon>mdi-xml</v-icon>
        </v-btn>        </a>


      </v-app-bar>
</div>
</template>
<script>
export default {

    data(){
        name:'navbar'
        return{
         /*   navbar:false,
    links: [

        {name: 'Linkedin',  logo: 'mdi-linkedin'},
        {name: 'Github',  logo: 'mdi-github'},
        {name: 'insta',  logo: 'mdi-instagram'},

]*/
}
        }

       



    }

</script>