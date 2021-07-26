<template>
<div>
  <v-footer padless color=""> 
    <v-col
      class="text-center white--text black"
      cols="12"
    >
      {{ new Date().getFullYear() }} — <strong>Made with Vuetify    <v-icon color="red">mdi-heart</v-icon>
      </strong>
    </v-col>
  </v-footer>  
</div>
  
</template>

<script>

export default {
    name:'footer',
    data() {
        return {
            
        }
    },
}
</script>