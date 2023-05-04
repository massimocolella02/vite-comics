<script>
import HeaderComp from './components/HeaderComp.vue';
import MainComp from './components/MainComp.vue';
import UtilitiesComp from './components/UtilitiesComp.vue';
import FooterComp from './components/FooterComp.vue';




export default{
  name: "App",
  components:{
    HeaderComp,
    MainComp,
    UtilitiesComp,
    FooterComp,
  }
}
</script>

<template>
  <div>
    <HeaderComp/>
    <MainComp/>
    <UtilitiesComp/>
    <FooterComp/>
  </div>
</template>

<style lang="scss">
@use "./style/main.scss" as *;
</style>
