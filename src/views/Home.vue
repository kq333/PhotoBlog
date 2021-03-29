<template>
  <div class="home">

      <Appbar/>
      <Home/>
      <Carousel/>
      <Content1/>
      <Footer/>

  </div>
</template>

<script>

import Carousel from '../components/Carusel.vue'
import Content1 from '../components/Content1.vue'
import Home from '../views/Home.vue'
import Appbar from '../components/Appbar.vue'
import Footer from '../components/Footer.vue'

export default {

  components: {

    Carousel,
    Content1,
    Appbar,
    Home,
    Footer,

  }
}
</script>
