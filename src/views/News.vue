<template>
  <div class="about">
    <h1>Novosti</h1>

     <zbroji-brojeve broj1="37" broj2="57"/>

    <moja-kartica naslov="Novost jedan" tekst="Moje ime je Ivan Raic" />
    <moja-kartica naslov="Novost dva" tekst="FPMOZ" />
    <moja-kartica naslov="Novost tri" tekst="Srednja strojarska" />

  </div>
</template>

<script>
import ZbrojiBrojeve from '../components/ZbrojiBrojeve.vue'
import MojaKartica from  '../components/MojaKartica.vue'

export default {
  components: { MojaKartica, ZbrojiBrojeve },
  name: 'ViseView',

}
</script>
