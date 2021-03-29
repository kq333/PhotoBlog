<template>
    <div >
        <v-container >
            <v-row >
            <v-col lg='3'>

            </v-col>
                <v-col  lg='6'>
                      <br>
                    <br>
                    <br>

                     <h1>Witamy na naszym blogu fotograficznym</h1>
                       <br>
                    <br>
                    <br>
                    <p>
                    <strong>
                        Darmowe sesje fotograficzne to znakomita okazja na wykonanie zdjęć przez profesjonalnych fotografów w naszym studiu fotograficznym 30 km od centrum Wrocławia. W zamian za swój czas otrzymasz od nas z pewnością wysokiej jakości zdjęcia, które zostaną doskonałą pamiątką na całe życie. My natomiast pozyskamy materiał do swojego dorobku artystycznego.
                    </strong>

                    <br>
                    <br>
                    <br>

                        <v-rov  >

                          <v-card>
                            <v-col v-for="item in items" :key="item" >
                                <v-img  :src="item.src"  > </v-img>
                            </v-col>
                            </v-card>
                        </v-rov>
                  <br>
                    <br>
                    <br>
 Męski portret - Darmowe sesje fotograficzne
Darmowe sesje fotograficzne, czy też inaczej Sesje “TFP” ( Time for Pictures – Czas za Zdjęcia) jest to sesja fotograficzna organizowana w naszym studiu fotograficznym 30km od Wrocławia lub w plenerze, w okolicach Wrocławia. Na sesji modelka/model wyraża zgodę pozowania do zdjęć a fotograf wykonuje zdjęcia przede wszystkim bez pozyskiwania korzyści finansowych.
<br>
                    <br>
                    <br>
Sesje takie służą przede wszystkim rozbudowaniu portfolio fotografa oraz modelki czy też modela. Zdjęcia wykonane na tego typu sesji mają charakter reprezentatywny, bez możliwości wykorzystania komercyjnego i dalszej odsprzedaży. Posiadają one rownież “znak wodny” naszego studia fotograficznego.
<br>
                    <br>
                    <br>
W rezultacie oznacza to, że zdjęcia z darmowej sesji fotograficznej możecie wykorzystać np. na portalach społecznościowych czy też wydrukować nie czerpiąc z tego jednak żadnych korzyści finansowych zarówno ze strony fotografa jak i ze strony modelki/modela<br>
                    <br>
                    <br>
<strong> KTO MOŻE ZGŁOSIĆ SIĘ NA BEZPŁATNĄ SESJĘ FOTOGRAFICZNĄ.</strong>
<br>
                    <br>
                    <br>
Na sesję taką może zgłosić się każdy, zarówno osoby z doświadczeniem w modelowaniu jak również te, które doświadczenia nie posiadają.  Jedynym warunkiem przystąpienia do takiej sesji jest ukończone 18 roku życia. Najważniejsza jest chęć oraz zaangażowanie podczas sesji.
<br>
                    <br>
                    <br>

Na bezpłatną sesję fotograficzną może zgłosić się również rodzina, kobieta w ciąży czy też mam z noworodkiem. Kryteria podane na tej stronie sporadycznie zmieniają się. Jeśli chcesz na bieżąco być informowany o dostępnych sesjach serdecznie zapraszamy do zapisania się do naszego biuletynu lub o sprawdzanie odwiedzanie naszej strony. W ten sposób z pewnością znajdziesz sesję dla Siebie.
<br>
                    <br>
                    <br>

<strong>KOGO OBECNIE POSZUKUJEMY NA DARMOWE SESJE FOTOGRAFICZNE.</strong>
<br>
                    <br>
                    <br>
Serdecznie zapraszamy wszystkich do zgłaszania się na sesje fotograficzne w naszym studiu w okolicy Wrocławia. Na chwilę obecną zapraszamy na:
<br>
                    <br>
                    <br>

<li><strong> sesje noworodkowe,</strong> </li> <br>
<li><strong> sesje ciążowe </strong></li>  <br>
<li><strong> męskie sesje portretowe </strong></li>  <br>
<br>
                    <br>
                    <br>

<strong> JAKIE WARUNKI TRZEBA SPEŁNIĆ, BY MÓC WZIĄĆ UDZIAŁ W DARMOWEJ FOTOGRAFICZNEJ?</strong>
<br>
                    <br>
                    <br>
Wypełnij formularz zgłoszeniowy (sekcja kontakt), polub naszą stronę na Facebook  Photography oraz udostępnij na swoim profilu nasz post dotyczący sesji TFP (możesz to zrobić klikając tutaj). Następnie wypełnij poniższy formularz. Podaj w nim swoje dane kontaktowe jak również namiary na portal społecznościowy (Facebook, maxmodels lub Instagram). Nie zapomnij napisać o preferencjach co rodzaju sesji, a także napisz kilka słów o sobie. W mailu zwrotnym otrzymasz niezbędne informacje.
<br>
                    <br>
                    <br>
                    <br>
                    <br>
                </v-col>
                  <v-col  lg='3' >
                </v-col>
                </v-row>
        </v-container>
    </div>
</template>

<script>
export default {
     data () {
      return {
        items: [
          {
              src: 'https://www.lebowskiphoto.pl/wp-content/uploads/2019/01/monia-1620x1080.jpg',
          },
          {
             src: 'https://www.lebowskiphoto.pl/wp-content/uploads/2018/12/portfolio-003-1620x1080.jpg',
          },

        ],
      }
    },
}
</script>

<style scoped>

p{
line-height: 1.5;
}

h1{
    justify-content: center;
    align-items: center;
    display: flex;
}



</style>