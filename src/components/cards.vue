<template>
    <div class="blue-grey darken-4">
      
 <!-- start proyectos web -->
      <v-layout column align-center>
                   <h2 class="text-sm-h2 error--text" xs12 sm12 >Proyectos</h2>

      </v-layout>
      <v-container  grid-list-md>
     
      <v-layout row wrap >
       
           



        <v-flex xs12 sm4  >
           <v-card>
              <v-img src="@/assets/img/peluqueria-maite.png"></v-img>
              <v-card-title text-center>

              </v-card-title>
              
                <v-card-actions > 
                   <v-layout column align-content-center>
                   <a href="https://maitevillarpeluqueros.netlify.app" 
  target="_blank" rel="noopener noreferrer" class="error--text">

                    <v-btn
                      text
                      block
                      class="error"
                        
                    >
                     Visitar pagina
                    </v-btn></a>
                </v-layout>        
 
                  </v-card-actions>
                
          </v-card>  
        </v-flex >

 <v-flex xs12 sm4                        
>
           <v-card >
              <v-img src="@/assets/img/capital.png"></v-img>
              <v-card-title>

              </v-card-title>
              
                  <v-card-actions>
                     <v-layout column align-content-center>
                  <a href="https://pecado-capital.netlify.app"
                    target="_blank" rel="noopener noreferrer" class="error--text">
                    <v-btn
                      text
                      block
                      class="error"
                        
                    >
                     Visitar pagina
                    </v-btn></a>
                </v-layout>
                   
                  </v-card-actions>
                
          </v-card>  

        </v-flex>

        <v-flex xs12 sm4 >
           <v-card>
              <v-img src="@/assets/img/tules.png"></v-img>
              <v-card-title>
               
              </v-card-title>
              <v-card-actions>
                
                 <v-layout column align-content-center>
                   <a href="https://tulesnovias.netlify.app" target="_blank"
                 rel="noopener noreferrer" class="error--text">
                    <v-btn
                      text
                      block
                      class="error"
                        
                    >
                     Visitar pagina
                    </v-btn></a>
                </v-layout>

               
                  </v-card-actions>
                
                
          </v-card>  
        </v-flex>

       



        </v-layout>
    </v-container>
<!-- end proyectos web -->

 <!-- start  knownledge -->

 <v-layout column align-center>
                   <h2 class="text-sm-h2 white--text" xs12 sm12 >Conocimientos</h2>

      </v-layout>

<v-container  grid-list-md>
     
      <v-layout row wrap >
       
          <v-flex xs12 sm4  >
           <v-card>
              <v-img src="@/assets/img/vue.png"></v-img>
              
              
                 
                
          </v-card>  
        </v-flex > 



        <v-flex xs12 sm4  >
           <v-card>
              <v-img src="@/assets/img/css.png"></v-img>
             
                 
          </v-card>  
        </v-flex >

 <v-flex xs12 sm4>
           <v-card>
              <v-img src="@/assets/img/materialize.png"></v-img>
             
                  
                
          </v-card>  

        </v-flex>

 




<v-flex xs12 sm4 >
           <v-card>
              <v-img src="@/assets/img/html.png"></v-img>
             
                
          </v-card>  
        </v-flex>

       
     <v-flex xs12 sm4  >
           <v-card>
              <v-img src="@/assets/img/js.png"></v-img>
              

                
          </v-card>  
        </v-flex >


      <v-flex xs12 sm4  >
           <v-card>
              <v-img src="@/assets/img/boostrap.png"></v-img>
              
              
                 
                
          </v-card>  
        </v-flex >

<v-flex xs12 sm4  >
           <v-card>
              <v-img src="@/assets/img/figma.png"></v-img>
              
              
                 
                
          </v-card>  
        </v-flex >




        </v-layout>
    </v-container>
 <!-- end  knownledge -->


 <!-- start  Learning  -->

<v-layout column align-center>
<h2 class="text-sm-h2 error--text Merienda" xs12 sm12 >Aprendiendo</h2>

      </v-layout>
      <v-container  grid-list-md>
     
      <v-layout row wrap >
       
           



        <v-flex xs12 sm4  >
           <v-card>
              <v-img src="@/assets/img/react.png"></v-img>
             
                 
                
          </v-card>  
        </v-flex >

 <v-flex xs12 sm4                       
>
<v-card>
              <v-img src="@/assets/img/node.png"></v-img>
              
              
                
          </v-card>  

        </v-flex>

<v-flex xs12 sm4 >
           <v-card>
              <v-img src="@/assets/img/mongodb.png"></v-img>
              
                
                
          </v-card>  
        </v-flex>

       
    


      



        </v-layout>
    </v-container>


 <!-- end  Learning  -->











    </div>
</template>


<style>
@import url('https://fonts.googleapis.com/css2?family=Merienda&display=swap');

</style>


<script>

export default {
    name: 'cards'
}
</script>