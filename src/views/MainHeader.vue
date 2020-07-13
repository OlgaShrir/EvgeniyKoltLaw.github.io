<template>
 <div class="main-header flex space-between align-items-center">
  <nav class="main-nav flex space-between align-items-center">
    <ul class="flex nav-items">
      <li><a href="#main" class="nav-item">Главная</a></li>
      <li><a href="#about" class="nav-item">О нас</a></li>
      <li><a href="#fields" class="nav-item">Юридические услуги</a></li>
      <li><a href="#contact" class="nav-item">Контакты</a></li>
    </ul>
  
    <div>
      <a href="#contact" class="contacts">
        <span>054-7504999 </span>
        <i class="fas fa-phone"></i>
      </a>
      <div>Адвокат Евгений Колт</div>
    </div>
  </nav>

 </div>
</template>

<script>
export default {
  name: 'MainHeader',
  components: {

  },
  methods: {
   
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/style/basic-style.scss";
.main-header{
  padding: 30rem 0;
  background-color: $color1;
  // position: sticky;
  // top: 0;
  // background-image: url(../assets/hammer.jpg);
}

.main-nav{
  width: 1100px;
  margin: auto;
  color: $color2;
  
}

li{
  padding-right: 30px;
}

.nav-item, .contacts{
  text-decoration: none;
  color: $color2;
  // font-size: 22px;
  // letter-spacing: 2px;
}

.nav-item:hover{
  border-bottom: 1px solid red;
  padding-bottom: 8rem;
}


 
</style>
