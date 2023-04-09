<template>
  <landingPage />
</template>

<script>
import LandingPage from './views/LandingPage.vue';
export default{
  components:{
    LandingPage
  }
}
</script>

<style scoped>

@font-face {
  font-family: "Poppins-Regular";
  src: url("./assets/fontFamilyPath/Poppins-Regular.ttf");
}

*{
  font-family: "Poppins-Regular",sans-serif;
  padding:0;
  margin:0;
  box-sizing: border-box;
}

</style>