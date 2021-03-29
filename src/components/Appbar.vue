<template>

  <div>
        <v-container>
          <v-app-bar
                    flat
                    dense fixed app
                    cols='12'
                    lg='12'
                    max-width='100%'
                >
                    <v-spacer></v-spacer>
                        <router-link  to="/" id='btn'>
                            <v-btn text >Home</v-btn>
                        </router-link>
                          <router-link   to="/gallery"  id='btn'>
                              <v-btn text >Galeria</v-btn>
                          </router-link>

                             <router-link   to="/about"  id='btn'>
                              <v-btn text >O nas</v-btn>
                          </router-link>

                            <router-link  to="/contact"  id='btn'>
                              <v-btn  text >Kontakt</v-btn>
                            </router-link>
          </v-app-bar>
          </v-container>
  </div>
</template>

<script>
  export default {
    name: 'App',


  }
</script>

<style scoped>

#btn{
   text-decoration-line: none;

}


</style>
