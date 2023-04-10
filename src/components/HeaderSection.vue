<template>
    <section class="heroSection">
        <img src="../assets/jessustature.png" alt="jesusStatus" class="JesusStature">
        <!-- marquee section -->
        <marquee>
            <img src="../assets/marquee.png" alt="marquee" class="Marquee">
            <img src="../assets/marquee.png" alt="marquee" class="Marquee">
            <img src="../assets/marquee.png" alt="marquee" class="Marquee">
            <img src="../assets/marquee.png" alt="marquee" class="Marquee">
            <img src="../assets/marquee.png" alt="marquee" class="Marquee">
            <img src="../assets/marquee.png" alt="marquee" class="Marquee">
            <img src="../assets/marquee.png" alt="marquee" class="Marquee">
            <img src="../assets/marquee.png" alt="marquee" class="Marquee">
            <img src="../assets/marquee.png" alt="marquee" class="Marquee">
            <img src="../assets/marquee.png" alt="marquee" class="Marquee">
            <img src="../assets/marquee.png" alt="marquee" class="Marquee">
            <img src="../assets/marquee.png" alt="marquee" class="Marquee">
            <img src="../assets/marquee.png" alt="marquee" class="Marquee">
            <img src="../assets/marquee.png" alt="marquee" class="Marquee">
            <img src="../assets/marquee.png" alt="marquee" class="Marquee">
        </marquee>
    </section>
</template>

<script>
</script>

<style scoped>
/* hero container style */
.heroSection{
    margin: auto;
    display:flex;
    flex-direction: column;
    justify-content: center;
    align-content: center;
    margin-top: -90px;
}

/* hero assets style  */
.JesusStature{
margin: auto;
max-width:70%;
}

marquee{
    width: 100%;
    z-index:1000;
    left:0;
    position:absolute;
    top:750px;
}

/* reponsiveness  */
@media screen and (max-width:480px) {
.heroSection{
    margin-top:-5px;
}
.JesusStature{
margin: auto;
max-width:100%;
} 

marquee{
    top:400px;
}
}

</style>