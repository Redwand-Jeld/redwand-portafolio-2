<template>
<div>
  <navbar/>

 
 <cards/>

  <footerDev/> 
</div>
  
</template>

<script>
import navbar from '@/components/navbar.vue'
import cards from '@/components/cards.vue'
import footerDev from '@/components/footerDev.vue'

  export default {
    name: 'Home',

    components: {
      navbar,
      cards,
      footerDev
    },
  }
</script>
