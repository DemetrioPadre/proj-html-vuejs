<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppCardCenter from './components/AppCardCenter.vue';
import AppFooter from './components/AppFooter.vue';



export default {
  data() {
    return {};
  },
  components: { AppHeader, AppMain, AppCardCenter, AppFooter }
};
</script>

<template>
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <AppCardCenter></AppCardCenter>
  <AppFooter></AppFooter>
</template>

<style lang="scss">
@use './assets/style/general.scss'
</style>
