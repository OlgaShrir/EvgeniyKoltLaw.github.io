<template>
 <div class="about-container">
    <h1>О нас</h1>
    <div class="about flex">
      <div class="img"><img src="../../public/img/portret.jpg" alt="Евгений Колт, адвокатский офис в Израиле"></div>
      <p>Наш офис специализируется в сфере гражданского права. В первую очередь мы ставим приоритет на эмпатию и личное участие в проблемах наших клиентов, делая все возможное в целях продвижения их интересов. Упорство, целенаправленность и приобретенный опыт помогают нам представлять интересы клиентов на высоком уровне. <br> Мы найдем для вас выход из самых сложных ситуаций.</p>
    </div>
 </div>
</template>

<script>
export default {
  name: 'AboutUs',
  components: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/style/basic-style.scss";
.about{
  margin-bottom: 80rem; 
}
h1{
  text-align: center;
  margin-bottom: 50px;
}

img{
  width: 300px;
}

p{
  margin-left: 20px;
}

 
</style>
