<template>
  <v-container>

    <v-card  width="500" >
        <v-carousel :show-arrows="false"  cycle >
          <v-carousel-item
            v-for="(item,i) in items"
            :key="i"
            :src="item.src"
            reverse-transition="fade-transition"
            transition="fade-transition"
          >

                <p id="text1">{{item.description}}</p>
                <p >{{item.name}}</p>


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
            name: 'Aleksandra', description:'Nigdy nie spodziewałem się, że zrobienie jednego dobrego zdjęcia zajmuje nawet kilkadziesiąt minut a tak właśnie było w moim wypadku. ' ,
            src: 'https://cdn.pixabay.com/photo/2016/03/23/04/01/woman-1274056_1280.jpg',
          },
          {
              name:'Ola', description:'Wow!!!! Wymagająca ze mnie osoba ale efekt finalny przerósł moje wyobrażenia.',
            src: 'https://cdn.pixabay.com/photo/2015/11/26/00/14/woman-1063100_1280.jpg',
          },
          {
            name:'Anna',description:'Współpraca z tak zdolnym fotografem to czysta przyjemność i ciekawe doświadczenie. Duże, przestronne studio, mega profesjonalny sprzęt i luźna atmosfera to naprawdę wyjątkowe połączenie. ',
             src: 'https://cdn.pixabay.com/photo/2017/08/01/08/29/people-2563491_1280.jpg',
          },
          {
              name:'Karol', description:'Bardzo przestronne, świetnie wyposażone studio w połączeniu z mega profesjonalizmem fotografa daje przepiękne, nietuzinkowe zdjęcia. ',

            src: 'https://cdn.pixabay.com/photo/2016/11/21/12/42/beard-1845166_1280.jpg',
          },

        ],
      }
    },
  }
</script>

<style scoped>

#text1{
    color:white;
    margin-top: 140%;

}

</style>