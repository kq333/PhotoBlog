<template>
    <div >
        <v-container id="demo">
             <Appbar/>
             <Contactpage/>

        </v-container>

         <Footer/>


    </div>
</template>

<script>

import Appbar from '../components/Appbar.vue'
import Footer from '../components/Footer.vue'
import Contactpage from '../components/Contactpage.vue'


export default {

     components: {


    Appbar,
    Footer,
    Contactpage,



  }

}
</script>

<style scoped>
#demo{
    min-height: 800px;
}
</style>