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
@font-face {
    font-family: "JosefinSans-Bold";
    src: url("./assets/fonts/JosefinSans-Bold.ttf");
}
@font-face {
    font-family: "JosefinSans-Regular";
    src: url("./assets/fonts/JosefinSans-Regular.ttf");
}


@font-face {
    font-family: "Nunito-Light";
    src: url("./assets/fonts/Nunito-Light.ttf");
}

@font-face {
    font-family: "Nunito-Reg";
    src: url("./assets/fonts/Nunito-Regular.ttf");
}

@font-face {
    font-family: "Nunito-Bold";
    src: url("./assets/fonts/Nunito-Bold.ttf");
}

@font-face {
    font-family: "Nunito-Light";
    src: url("./assets/fonts/Nunito-Light.ttf");
}


*, 
*::after,
*::before {
    margin: 0;
    padding: 0;
    box-sizing: inherit;
    font-family: 'JosefinSans-Bold', 'Nunito-Bold';
}
html{
    font-size: 62.5%;
}
body{
    font-family: 'JosefinSans-Bold', 'Nunito-Bold';
    font-weight: 400;
    line-height: 1.7;
    padding:0rem;
    box-sizing: border-box;
}
</style>
