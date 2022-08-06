<template>
  <div class="about">
    <h1>This is profile page. My name is Ivan</h1>

     <zbroji-brojeve broj1="37" broj2="57"/>

    <moja-kartica naslov="Prva kartica" tekst="Moja prva komponenta u Vuejsu" />
    <moja-kartica naslov="Druga kartica kartica" tekst="Moja druga komponenta u Vuejsu" />
    <moja-kartica naslov="Treca kartica" tekst="Moja treca komponenta u Vuejsu" />

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
