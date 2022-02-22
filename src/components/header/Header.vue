<template>
    <div class="jumbo d-flex flex-column">
        <Menu :navbar="navbar"/>
        <Jumbo title-jumbo="MAKE A DIFFERENCE" 
               paragraph-jumbo="As long as poverty injustice &amp; inequality persist, none of us can truly rest"/>
    </div>
</template>

<script>
import Menu from './Menu.vue' 
import Jumbo from './Jumbo.vue' 

export default {
    name:'Header',
    props:['navbar'],
    components:
    {
        Menu,
        Jumbo,
    },
}
</script>

<style lang="scss" scoped>
.jumbo
{
        background-image: url("../../assets/images/home-page-slider.jpg");
        background-position: center;
        background-repeat: no-repeat;
        background-size:cover;
        height: 600px;

       
}
</style>