
<template>
<nav>
    <h2 class="logo">Jesus</h2>
    <ul>
        <li v-for="x in this.links">
        <a v-bind:href="x.linksId">{{ x.linkObj }}</a>
        </li>
    </ul>
</nav>
</template>

<script>
export default{
    data(){
        return{
            links:[
                {linksId:'#Community',linkObj:"Community"},
                {linksId:'#About',linkObj:"About"},
                {linksId:'#Teams',linkObj:"Teams"},
            ]
        }
    }
}
</script>

<style scoped>
nav{
    padding: 2px 20%;
    display: flex;
    justify-content: space-between;
    margin:auto;
    align-content: center;
    position: relative;
}

.logo{
    font-size:1.3rem;
}

ul{
    display: flex;
    justify-content: center;
    margin:auto;
    gap:7em;
    align-content: center;
}
a,li{
    color:black;
    list-style-type: none;
    text-decoration: none;
}

/* navigation pointers */
li::before{
    content: "";
    position: absolute;
    border:2px solid;
    width:0%;
    bottom: 23%;
    display: none;
}

li:hover::after{
    content: "";
    position: absolute;
    border:2px solid;
    width:5%;
    bottom: 23%;
    display: block;
    transition: linear ,1000ms;
}

/* responsiveness */
@media screen and (max-width:480px){
    ul{
        display: none;
    }
    nav{
        padding: 6px 6%;
    }
}
</style>