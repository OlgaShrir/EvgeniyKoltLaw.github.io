<template>
  <div class="citation-container">
    <div class="citation">
      <p>« Когда справедливость исчезает, то не остается ничего, что могло бы придать ценность жизни людей »</p>
      <p>Иммануил Кант</p>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Citation',
  components: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/style/basic-style.scss";
.citation-container{
  width: fit-content;
   
}
.citation{

  margin: 80rem 0 80rem 010vw;
  border: 1px solid $color3;
  border-radius: 10px;
  padding: 30rem;
}
p{
  direction: rtl;  
  // font-size: 18px;
  font-style: italic;
}
</style>
