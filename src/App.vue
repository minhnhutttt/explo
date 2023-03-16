<template>
  <HeaderMain />
  <HomeSearch />
  <div class="" :style="{
      backgroundImage: 'url(' + require('@/assets/images/bg-main.png') + ')',
    }">
    
  </div>
</template>

<script>
import HeaderMain from './components/Header/HeaderMain.vue';
import HomeSearch from './components/HomeSearch.vue';

export default {
  name: 'App',
  components: {
    HeaderMain,
    HomeSearch
}
}
</script>

