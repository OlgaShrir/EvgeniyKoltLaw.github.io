<template>
 <div class="footer">
     
    <div class="contacts">
      <p>Контакты</p>
      <p>Телефон: 054-7504999</p>
      <p>Эл. Почта: Evgeniyk.law@gmail.com</p>
      <p>Адрес: ул. Аарбаа 28, комплекс «Мигдалей Хаджадж», Северное здание, 3-й этаж, Тель Авив</p>
    </div>
    
    
 </div>
</template>

<script>
export default {
  name: 'ContactUs',
  components: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/style/basic-style.scss";
.footer{
  background-color: $color1;
  color: white;
  page-break-after: 100px;
}
.contacts{
  width: 1100px;
  margin: auto;
  padding: 30rem 0;
  // padding: 40px 60px;
  // padding: 40px 0;
  // font-size: 22px;
  // letter-spacing: 2px;
}
 
</style>
