<template>
  <BaseContainer />
</template>

<script>
import BaseContainer from './components/Base.vue'

export default {
  name: 'App',
  components: {
    BaseContainer
  }
}
</script>

<style>
*, 
*::after,
*::before {
    margin: 0;
    padding: 0;
    box-sizing: inherit;
}
html{
    font-size: 62.5%;
}
body{
    font-family: 'Helvetica Neue', sans-serif;
    font-weight: 400;
    line-height: 1.7;
    padding:0rem;
    box-sizing: border-box;
}
</style>
