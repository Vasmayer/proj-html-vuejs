<template>
<div class="jumbo d-flex flex-column">
        <nav class="navbar navbar-expand-lg">
            <div class="container-fluid">
                <a class="navbar-brand" href="#"><img :src="require('../assets/images/avada-charity-logo.png')" alt="Logo Avada"></a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse">
                    <div class="navbar-nav flex-grow-1 justify-content-end align-items-center">
                        <a class="nav-link" :class="i===0 ? 'active': ''" v-for="(link,i) in navbar" :key="i" href="#">{{link}}</a>
                        <a class="nav-link">
                            <Button content="donate" type="normal"/>
                        </a>
                    </div>
                </div>
            </div>
        </nav>
        <div class="flex-grow-1 position-relative">
            <div class="position-absolute top-50 start-50 translate-middle text-light">
              <h1 class="text-center">MAKE A DIFFERENCE</h1>
              <p>As long as poverty injustice &amp; inequality persist, none of us can truly rest</p>
              <div class="text-center">
                <Button content="our mission" type="outlined-white"/>
                <Button content="donate now" type="outlined-yellow"/>
              </div>
            </div>
        </div>
</div>
       
</template>

<script>
import Button from './Button.vue' 

export default {
    name:'Navbar',
    props:['navbar'],
    components:
    {
        Button,
    },
}
</script>

<style lang="scss" scoped>
@import '../assets/scss/_vars.scss';

.jumbo
{
        background-image: url("../assets/images/home-page-slider.jpg");
        background-position: center;
        background-repeat: no-repeat;
        background-size:cover;
        height: 600px;

        p
        {
            font-size: 13px;
        }
}
.navbar
{
    .nav-link
    {
        color: $menu-color;
        text-transform: uppercase;
        font-size: 10px;
        margin: 10px 15px;
        cursor: pointer;
    }
    .active
    {
        color: $menu-active;
    }
    .navbar-brand
    {
        img{
            width: 200px;
            margin-left: 50px;
        }
    }
}
</style>