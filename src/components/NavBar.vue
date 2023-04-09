<template>
<nav>
    <b class="navBarLogo">Jesus.</b>
    <ul>
        <li><a href="#Home">Home</a></li>
        <li><a href="#About">About</a></li>
        <li><a href="#Community">Community</a></li>
    </ul>
</nav>
</template>

<script>
export default{

}
</script>

<style scoped>
.navBarLogo{
    font-size: 23px;
    font-weight: bolder;
}

nav{
    padding-top: 20px;
    margin:0px auto;
    display: flex;
    justify-content: center;
    align-items: center;
    min-width:70vw;
    align-content: center;
}

ul,li {
    gap:7em;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    list-style-type: none;
    position: relative;
}

li,a{
    color:black;
    text-decoration: none;
}

li::before{
content: "";
position:absolute;
width:0%;
border: 2px solid black;
bottom:-4px;
opacity:0%;
}

li:hover::after{
content: "";
position:absolute;
width:100%;
border: 2px solid black;
bottom:-4px;
opacity:100%;
}

</style>