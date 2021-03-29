<template>
    <div>

                <v-row>
                  <v-col lg='12' md='12' sm='12' xs='12'>
                        <br>

                <h1>O NAS</h1>
                <br>
                <br>
                <v-divider></v-divider>
                        <br>

                      </v-col>


                    <v-col id='img' lg="6"  md='6' sm='6' xs='6' >

                                <v-col lg="6" v-for="item in items"   :key="item">
                                    <v-card>
                                         <v-img :src="item.src"   ></v-img>
                                    </v-card>
                                </v-col>
                                </v-col>

            <v-col lg="6"  md='6' sm='6' xs='2' id='text' >



<br>

   <h2>MONIKA,</h2> <br>
fotograf i założycielka studia TWÓJ<strong>PSTRYK</strong>
<br>



<br>
<strong> Miło, że zajrzałeś tu, aby dowiedzieć się o nas nieco więcej. Mamy nadzieję, że znalazłeś się tutaj, ponieważ uwielbiasz twórczą, zrelaksowaną fotografię. </strong>
 <br><br>

Jako szczęśliwa żona i mama dwójki dzieci doskonale rozumiem, jak ważne jest zatrzymywanie w kadrach ulotnych chwil z życia rodzinnego. Moment, w którym spodziewacie się dziecka, a potem jego pierwsze dni, uśmiechy i grymasy są niepowtarzalne i niestety krótkotrwałe.

 <br><br>

W sferze zawodowej specjalizuję się w fotografii ciążowej, noworodkowej, dziecięcej i rodzinnej. Uwielbiam fotografować kobiety noszące pod sercem swoje dziecko, a kilka tygodni później móc utulać to maleństwo do snu i pozycjonować do pięknych zdjęć. To naprawdę niesamowite doświadczenie!

 <br><br>

Cud nowego życia nieustannie mnie zachwyca i inspiruje do pracy, co odzwierciedla się w ponadczasowych kadrach przepełnionych Waszą wspólną miłością i czułością. Jestem przekonana, że niejednokrotnie będziecie wracać do swoich rodzinnych albumów ocierając ukradkiem łzy wzruszenia.

 <br><br>

Dążenie do perfekcji w swojej dziedzinie pracy traktuję jako priorytet, dlatego każdą wolną chwilę poświęcam na kursy i szkolenia fotograficzne indywidualne oraz grupowe, co nieustannie rozwija mój warsztat i umiejętności.

 <br><br>
                    </v-col>

                </v-row>

    <v-row>


                    <v-col id='img' lg="6"  md='6' sm='6' xs='6'>
                                <v-col lg="6"
                                    v-for="image in images"
                                    :key="image">
                                    <v-card>
                                         <v-img :src="image.src"   ></v-img>
                                    </v-card>
                    </v-col>
                                </v-col>


<v-col lg="6" id='text'>
<br>


   <h2>MARIUSZ,</h2> <br>
fotograf i retuszer
<br>


<br>
<strong>Odkąd pamiętam fotografia towarzyszyła mi w każdym istotnym momencie mojego życia. Trzymałem aparat w dłoni, by uwiecznić wszystko to, co piękne lecz ulotne. </strong>
 <br><br>

Wierzę, że ludzie są najbardziej interesującymi stworzeniami na planecie. Choć może brzmieć to nieco banalnie, sądzę, że każdy jest wyjątkowy – ma inny wygląd, osobowość, potrzeby i oczekiwania.

 <br><br>

Dobry fotograf jest przede wszystkim dobrym psychologiem. Na naszych sesjach fotograficznych zawsze staram się stworzyć przyjazną atmosferę, aby modele mogli czuć się zrelaksowani i wyglądać bardziej naturalnie, co jest podstawą odzwierciedlenia prawdziwej osobowości na fotografii.

 <br><br>

Poza fotografią zajmuję się również od wielu lat grafiką komputerową ze specjalizacją retuszera, więc poza aparatem w naszym studiu spędzam znaczną ilość czasu z komputerem i nowoczesnymi technologiami grafiki komputerowej.

 <br><br>

Serdecznie zapraszam wszystkich do naszego studia na niepowtarzalne sesje fotograficzne

 <br><br>
                    </v-col>
                </v-row>

<br><br><br><br>

<v-divider></v-divider>
<br><br><br><br>

    <v-row>
        <v-col lg='12'>
             <h1>CO O NAS MÓWIĄ</h1>
        </v-col>
    </v-row>
    <br><br>

    <v-row>

    <v-col lg="4">

    </v-col>


<v-col  lg='6'>

        <Opinion/>

</v-col>

<v-col lg="1">

</v-col>

</v-row>






<br><br>

<v-divider></v-divider>


<br><br>
<br><br>



<v-row >
    <v-col id="img">
                                <v-col lg="6"
                                    v-for="dd in dds"
                                    :key="dd">
                                    <v-card width='300'>
                                    <v-img :src="dd.src"  width='300' ></v-img>
                                    </v-card>
                                </v-col>
</v-col>




            <v-col lg='6'>
                <p id="text">
                    <br><br>
                   <strong>ZALETY WSPÓŁPRACY</strong>
                   <br><br>
                    <strong>Nasza Filozofia</strong>

                    <br>
                    Fotografia to zatrzymywanie w kadrze ulotnych radości, zabawnych sytuacji i chwil pełnych wzruszeń. To przecież wspaniałe opowieści Waszego życia. Uwielbiamy układać w albumy barwne foto-historie z niewielkiej części Waszego czasu, którym postanowiliście się z nami podzielić. Jesteście dla nas wielką inspiracją i natchnieniem.
                </p>

            </v-col>
</v-row>
    </div>
</template>

<script>



import Opinion from '../components/Opinion.vue'


export default {

    components:{
            Opinion
    },

     data () {
      return {
        items: [
          {
              src: 'https://cdn.pixabay.com/photo/2021/03/22/16/07/woman-6115105_960_720.jpg',
          },

        ],

        images:[
            {
                src:'https://cdn.pixabay.com/photo/2017/12/31/15/56/portrait-3052641_960_720.jpg'
            }
        ],

         dds:[
            {
                src:'https://cdn.pixabay.com/photo/2016/01/09/18/27/camera-1130731_1280.jpg'
            }
        ]
      }
    },
}
</script>

<style scoped>
#img{
    display:flex;
    justify-content: flex-end;
}

#text{
    line-height: 1.5;
    text-align: justify;
}

h1{
    display: flex;
    justify-content: center;
    text-align: center;
    text-decoration: underline;
    text-decoration-color: rgba(126, 189, 26, 0.63);
}

h2{

    text-decoration: underline;
    text-decoration-color: rgba(189, 173, 26, 0.63);
}

#col{
    display: flex;
    justify-content:center;


}

</style>