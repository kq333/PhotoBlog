<template>
  <div class="about">
    <v-container>
       <Appbar/>
       <Aboutus/>

    </v-container>


      <Footer/>


  </div>
</template>




<script>

import Appbar from '../components/Appbar.vue'
import Footer from '../components/Footer.vue'
import Aboutus from '../components/Aboutus.vue'


export default {

     components: {


    Appbar,
    Footer,
    Aboutus




  }






}
</script>
