<template>
    <section class="footerSection">
        <div class="footerdetails">
            <h2 class="footerLogo">Jesus</h2>
        </div>
    
    </section>

</template>

<script>
</script>

<style>
.footerSection{
    position: absolute;
    width:100%;
    height: 40vh;
    background-color: black;
    z-index: 1000;
    left: 0;
    display: flex;
}

.footerdetails{
    padding: 30px 12%;
    color:white;
}

@media screen and (max-width:480px) {
    .footerLogo{
        font-size:20px;
    }
}
</style>