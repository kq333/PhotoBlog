<template>
  <v-container>
    <v-card>
        <v-carousel :show-arrows="false"  cycle >
          <v-carousel-item
            v-for="(item,i) in items"
            :key="i"
            :src="item.src"
            reverse-transition="fade-transition"
            transition="fade-transition"

          >
          </v-carousel-item>
        </v-carousel>
        </v-card>
  </v-container>
</template>

<script>
  export default {
    data () {
      return {
        items: [
          {
            src: 'https://cdn.pixabay.com/photo/2014/10/30/17/32/boy-509488_1280.jpg',
          },
          {
            src: 'https://cdn.pixabay.com/photo/2021/02/24/23/45/couple-6047792_1280.jpg',
          },
          {
            src: 'https://cdn.pixabay.com/photo/2021/01/08/17/02/old-man-5900410_1280.jpg',
          },
          {
            src: 'https://cdn.pixabay.com/photo/2012/03/04/01/01/father-22194_1280.jpg',
          },
           {
            src: 'https://cdn.pixabay.com/photo/2020/12/15/13/44/portrait-5833683_1280.jpg',
          },
        ],
      }
    },
  }
</script>