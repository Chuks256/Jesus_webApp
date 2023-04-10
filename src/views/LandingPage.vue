<template>
<div class="containerWrapper">
    <NavBar/>
    <HeaderSection />
    <AboutSection/>
    <FootSection />
</div>
</template>


<style scoped>
*{
    user-select: none;
    user-zoom: none;
}
</style>

<script>
import FootSection from "../components/FootSection.vue"
import NavBar from "../components/NavBar.vue"
import HeaderSection from "../components/HeaderSection.vue"
import AboutSection from "../components/AboutSection.vue"
export default{
components:{
    NavBar,
    HeaderSection,
    AboutSection,
    FootSection
}
}
</script>