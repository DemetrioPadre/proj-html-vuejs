<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppCardCenter from './components/AppCardCenter.vue';
import AppCardSec from './components/AppCardSec.vue';
import AppPlayer from './components/AppPlayer.vue';
import AppCarousel from './components/AppCarousel.vue';
import AppFooter from './components/AppFooter.vue';



export default {
  data() {
    return {};
  },
  components: { AppHeader, AppMain, AppCardCenter, AppPlayer, AppCardSec, AppCarousel, AppFooter }
};
</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <AppCardCenter></AppCardCenter>
  <AppPlayer></AppPlayer>
  <AppCardSec></AppCardSec>
  <AppCarousel></AppCarousel>
  <AppFooter></AppFooter>
</template>

<style lang="scss">
@use './assets/style/general.scss'
</style>
