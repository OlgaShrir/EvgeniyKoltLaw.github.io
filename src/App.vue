<template>
  <div id="App">

    <MainHeader id="header" class="view full"/>
    <Citation id="citation" class="view"/>
    <MainPage id="main" class="view"/>
    <AboutUs id="about" class="view"/>
    <ActivityFields id="fields" class="view"/>
    <ContactUs id="contact" class="view full"/>


    
  </div>
</template>

<script>
import MainHeader from '@/views/MainHeader.vue'
import Citation from '@/views/Citation.vue'
import MainPage from '@/views/MainPage.vue'
import AboutUs from '@/views/AboutUs.vue'
import ActivityFields from '@/views/ActivityFields.vue'
import ContactUs from '@/views/ContactUs.vue'

export default {
  components: {
    MainHeader,
    Citation,
    MainPage,
    AboutUs,
    ActivityFields,
    ContactUs
  }
};
</script>

<style>
.view:not(.full){
  width: 80vw;
  margin: auto;
  
}

</style>