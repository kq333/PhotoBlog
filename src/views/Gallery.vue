<template>
    <div class="gallery" >
        <v-container>
              <Appbar/>

                <h1 >Galeria</h1>

                        <v-row>
                            <v-col  lg='12' sm="12" offset-sm="12"  >
                                <v-card>
                                    <v-container fluid>
                                    <v-row>
                                        <v-col
                                        v-for="n in 18"
                                        :key="n"
                                        class="d-flex child-flex"
                                        cols="4"
                                        >
                                        <v-card flat tile class="d-flex">
                                            <v-img
                                            :src="`https://picsum.photos/1600/1600?image=${n * 5 + 10}`"
                                            :lazy-src="`https://picsum.photos/10/6?image=${n * 5 + 10}`"
                                            aspect-ratio="1"
                                            class="grey lighten-2"

                                            >
                                            <template v-slot:placeholder>
                                                <v-row
                                                class="fill-height ma-0"
                                                align="center"
                                                justify="center"
                                                >
                                                <v-progress-circular indeterminate color="grey lighten-5"></v-progress-circular>
                                                </v-row>
                                            </template>
                                            </v-img>
                                    </v-card>
                            </v-col>
                        </v-row>
        </v-container>
      </v-card>
    </v-col>
  </v-row>
        </v-container>
          <Footer/>
    </div>
</template>

<script>

import Appbar from '../components/Appbar.vue'
import Footer from '../components/Footer.vue'


export default {

    components: {


    Appbar,
    Footer,


  }

}


</script>