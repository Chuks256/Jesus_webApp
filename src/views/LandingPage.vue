<template>
<div class="containerWrapper">
    <NavBar/>
    <HeaderSection />
    <AboutSection/>
</div>
</template>


<style scoped>
.containerWrapper{  
display: flex;
align-content: center;
justify-content: center;
flex-direction: column;
position: absolute;
left: 0;
top:0;
}
</style>

<script>
import NavBar from "../components/NavBar.vue"
import HeaderSection from "../components/HeaderSection.vue"
import AboutSection from "../components/AboutSection.vue"
export default{
components:{
    NavBar,
    HeaderSection,
    AboutSection
}
}
</script>