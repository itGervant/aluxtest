<template>
  <div class="home">
    <MyBanner />
    <MyPage  />
    <RoutPage />
    <AboutPage />
  </div>
</template>

<script>

import MyBanner from '@/components/MyBanner.vue';
import MyPage from '@/components/MyPage.vue';
import RoutPage from '@/components/RoutPage.vue'
import AboutPage from '@/components/AboutPage.vue';

export default {
  name: 'HomeView',
  components: {
     MyBanner, MyPage, RoutPage, AboutPage
  }
}
</script>

<style >
p {
 margin-bottom: 20px;   
 font-family: 'Montserrat';
font-style: normal;
font-weight: 500;
font-size: 18px;
line-height: 154%;
/* or 28px */


/* Grey font */

color: #72767E;
}

</style>
