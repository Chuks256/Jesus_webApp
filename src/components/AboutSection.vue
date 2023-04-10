<template>
    <section class="AboutSectionContainer">
        <div class="AboutTxtContainer">
            <h2 class="JesusStroke">Who is Jesus ?</h2>
            <b class="jesusStrokeDetails">Who is Jesus ?</b>
        </div>
        <!-- about section details -->
        <section class="DetailsSection">
            <div class="FirstCol">
                <img src="../assets/king.png" alt=" Theking" class="King">
                <h2 class="firstDetailsTxt">He Is The King Of Kings </h2>
            </div>

            <!-- second column detail -->
            <div class="secondCol">
                <img src="../assets/intercessor.png" alt="intercessorCircle" class="intercessorPng">
                <img src="../assets/interceeding.jpg" alt=" Theking" class="intercessorKing">
                <h2 class="secondDetailsTxt">He Is Our Intercessor </h2>
            </div>

            <!-- third column detail -->
            <div class="thirdCol">
                <img src="../assets/crucified.jpg" alt=" Theking" class="intercessorKing">
                <h2 class="secondDetailsTxt">He Is The Saviour Of The World</h2>
            </div>

            <!-- fourh details -->
            <div class="ascending">
                <img class="ascendImg" src="../assets/ascending.png" alt="ascendImg">
                <h2 class="ascendingText">Be Part Of This Journey By Giving Your Life To Him</h2>
            </div>

        </section>
      
      
    </section>
   
</template>

<script>
</script>

<style scoped> 
@font-face {
    font-family: 'Poppins-Black';
    src: url("../assets/fontFamilyPath/Poppins-Black.ttf");
}

.AboutSectionContainer{
    margin:auto;
    flex-direction: column;
    display:flex;
    padding: 12%;
    justify-content: center;
    align-items: center;
    align-content: center;
 }

.JesusStroke{
font-family: 'Poppins-Black',sans-serif;
-webkit-text-stroke: 2px black;
-webkit-text-fill-color: transparent;
font-size: 50px;
}

.jesusStrokeDetails{
    position: absolute;
    bottom: -340px;
    display: flex;
    align-content: center;
    justify-content: center;
    left: 530px;
    font-size:2rem;
}

/* columnssection style */
.DetailsSection{
padding:40px
}
.FirstCol{
    display: flex;
    flex-direction: row;
    margin:auto;
}
/* responsiveness mobile */
.firstDetailsTxt, .secondDetailsTxt{
    padding:20px;
}

.secondDetailsTxt{
    padding-top: 150px;
}

/* second details */
.secondCol{
display: flex;
flex-direction: row-reverse;
padding-top: 100px;
gap:10em
}

.intercessorKing{
    max-width:350px;
    object-fit:cover;
}

/* third column */
.thirdCol{
    display:flex;
    flex-direction: row;
    gap:5em;
    padding-top: 60px;
}

/* fourth column */
.ascending{
        padding-top:100px;
        display: flex;
        align-items: center;
        align-content: center;
        justify-content: center;
        flex-direction: column;
        text-align: center;
    }
    .ascendImg{
        max-width:500px;
        /* position: absolute; */
    }

    .ascendingText{
        font-size:20px;
        width:300px;
    }

    .intercessorPng{
        position: absolute;
       right:490px;
       animation-name:intercessorPng;
       animation-duration:1000ms;
       animation-iteration-count: infinite;
       animation-delay: 1000ms;
       transition:linear ,1000ms;
    }

    @keyframes intercessorPng {
        from{
            transform:rotate(0deg)
        }
        to{
            transform:rotate(360deg)
        }
    }

@media screen and (max-width:480px) {
    .AboutSectionContainer{
        padding-top:50% ;
        display: flex;
    }

    .AboutTxtContainer{
        display: flex;
        margin: auto;
        flex-direction: column;
    }

    .jesusStrokeDetails{
        font-size: 25px;
        left:10px;
        bottom: 110px;
        position: relative;
    }

    .JesusStroke{
        font-size:35px;
    }

    /* colum details sectionresponsiveness */

    .FirstCol{
        flex-direction: column;
        align-content: center;
        justify-content: center;
        align-items: center;
    }
    

    .King{
        max-width: 300px;
    }

    .firstDetailsTxt{
        padding: 10px;
        font-size:20px;
    }

    /* second details */
    .secondCol{
        flex-direction: column;
        padding-top:50px;
        gap:0.5em;
    }

    .secondDetailsTxt{
        padding-top:5px;
        font-size:20px;
    }

    .intercessorKing{
        max-width:300px;
    }

    .thirdCol{
        flex-direction: column;
        gap:0em;
        padding-top:30px;
    }

    /* fourth section */
    .ascending{
        padding-top:100px;
    }
    .ascendImg{
        max-width:300px;
    }
    .ascendingText{
        width:300px;
    }

    .intercessorPng{
        width:20%;
        left:10px
    }
}
</style>