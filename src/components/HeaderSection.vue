<template>
<section class="heroSection">
    <img src="../assets/jessustature.png" alt="JesusStature"  class="HeroImg">
    </section>
    <div class="dcon">
        <marquee class="d" behavior="infinite" direction="forward">
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">        
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">      
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">        
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">        
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">      
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">        
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">        
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">      
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">        
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">  
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">      
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">        
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">        
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">      
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">        
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">        
        <img src="../assets/marquee.png" alt="Marque"  class="HeroMarquee">        
    </marquee>
   
    </div>
</template>

<script>
import FootSection from "../components/FootSection.vue"
export default{
    components:{
        FootSection
    }
}
</script>

<style scoped>
.heroSection{
    display: flex;
    margin: auto;
    margin-top: -20px;
}

.HeroImg{
    
}

.dcon{
    display: flex;
    flex-direction: row;
}
.HeroMarquee{
}

.heroSection{
    display: flex;
    align-content: center;
    justify-content: center;
    flex-direction: column;
}

</style>