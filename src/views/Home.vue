<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <header-shayna/>
    <hero-shayna/>
    <content-shayna/>
    <footer-shayna/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue';
import HeaderShayna from '@/components/HeaderShayna.vue';
import HeroShayna from '@/components/HeroShayna.vue';
import ContentShayna from '@/components/ContentShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroShayna,
    ContentShayna,
    FooterShayna
    // HelloWorld
  },
  data(){
    return{
      member:{
        name: 'try',
        coverImg: "img/hero-2.jpg"
      }
    }
  }
}
</script>
