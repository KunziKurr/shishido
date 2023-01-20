<template>
  <div class="base">
    <HeaderSection />
    <!-- end of header section -->
    <!-- base component -->
    <div class="base_container">

    </div>
  </div>
</template>

<script>
import HeaderSection from './Header.vue'
export default {
  name: 'BaseContainer',
  components:{
      HeaderSection
  }

}
</script>

<style lang="scss">
.base{
    position: relative;
    width: 100%;
    &_container{
        width:100vw;
        height: 100vh;
        position: fixed;
        left: 0;
        right: 0;
        top:0;
        bottom:0;
        display: flex;
        // color presets
           background-image: linear-gradient(45deg, #1e2c4c 24%, rgb(30 44 76 / 78%) 61%);
           z-index: -1;


    }
}
</style>
