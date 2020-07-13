<template>
<div class="main-container">
  <div class="main">

    <!-- <div class="img-container">
      <img src="../../public/img/logo.png" alt="Евгений Колт, адвокатский офис в Израиле">
    </div> -->

    <h1>Адвокатский офис в Израиле</h1>
    <div>
      <p>Наш офис оказывает услуги в сфере гражданского права, при этом наша основная специалиция -  помощь в урегулировании долгов, а также в получении страховых возмещений вследствие дорожно-транспортных происшествий (ДТП) и производственных травм.</p>
      <p>Полный перечень наших услуг можно увидеть в рубрике <a href="#fields">Юридические услуги</a></p>
      <p>Мы находится в  нескольких минутах от торгового центра Азриэли по адресу ул. Аарбаа 28 Тель авив</p>

    </div>
 </div>
</div>
</template>

<script>
export default {
  name: 'MainPage',
  components: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/style/basic-style.scss";
.main-container{
}
.main{
  // margin: 100px 0;
  margin-bottom: 80rem; 
  
}
h1{
  text-align: center;
  // margin-bottom: 50px;
}
a{
  text-decoration: none;
  color: black;
}

</style>
