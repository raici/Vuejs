<template>

  <div class="kartica">
    <h1>{{naslov}}</h1>

    <p class="kartica_tekst"> {{ tekst }}</p>
  </div>
 


</template>

<script>
export default {
  name: 'MojaKartica',
  props:['naslov','tekst'] 
    
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.kartica{
  border: 3px solid #ccc;
  padding:10px;
  margin: 10px;
  border-radius: 3px;
  box-shadow: #ccc;
}

.kartica_tekst{
  margin-top: 30px;
}

</style>
