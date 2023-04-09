<template>
<section>
    <div class="textAbout">
        <b class="textBold">Who is Jesus ?</b>
    <h2>Who is Jesus ?</h2>
    </div>
    <!-- about section explainng jesus  -->
    <div class="ColContainer">
        <div class="firstCol">
        <img  src="../assets/king.png" class="kingImg"/>
        <h1 class="kingText">He Is The King Of Kings</h1>
    </div>
    <br><br><br>
    <!--intercessor section  -->
    <div class="secondCol">
        <img src="../assets/intercessor.png" class="intercessorCircle" />
        <img  src="../assets/interceeding.jpg" class="kingIntercessor"/>
        <h1 class="kingTextIntercessor">He Is Our Intercessor</h1>
    </div>
    </div>
</section>
</template>

<script>
</script>

<style scoped>
@font-face{
    font-family: "Poppins-Black";
    src:url("../assets/fontFamilyPath/Poppins-Black.ttf")
}

section{
    display: flex;
    margin: auto;
    justify-content: center;
    align-content:center ;
    padding:1px;
    flex-direction: column;
}
h2{
font-family: "Poppins-Black",sans-serif;
-webkit-text-stroke:2px black;
-webkit-text-fill-color: transparent;
font-size: 60px;
}

.textBold{
    text-align: center;
    position: absolute;
    margin-top:42px;
    display: flex;
    font-size:2rem;
    font-family:"Poppins-Black",sans-serif;
}

.textAbout{
    flex-direction: row;
    display: flex;
    justify-content: center;
    align-content: center;
}
/*  about column design  */
.firstCol{
    display: flex;
    flex-direction: row;
    gap:8em;
}
.kingText{
    padding:10% 10px;
}

.kingIntercessor{
width:475px;
height: 450px;
object-fit:cover;
}

.secondCol{
    display: flex;
    flex-direction: row-reverse;
    gap:8em;
    padding-top:30px;
}

.kingTextIntercessor{
    padding:10% 10px;
}

.intercessorCircle{
    position: absolute;
    bottom: 15%;
    right:40%;
    transition: linear, 1000ms;
    animation-name: intercessorCircle;
    animation-duration: 5000ms;
    animation-iteration-count: infinite;
    animation-delay: 1ms;
}

@keyframes intercessorCircle {
    from{
        transform:rotate(0deg);
    }
    to{
        transform:rotate(360deg)
    }
}

</style>