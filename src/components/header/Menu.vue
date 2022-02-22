<template>
     <nav class="navbar navbar-expand-lg navbar-dark bg-trasparent">
            <div class="container-fluid">
                <a class="navbar-brand" href="#"><img :src="require('../../assets/images/avada-charity-logo.png')" alt="Logo Avada"></a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse">
                    <div class="navbar-nav flex-grow-1 justify-content-end align-items-center">
                        <a class="nav-link" :class="i===0 ? 'active-link': ''" v-for="(link,i) in navbar" :key="i" href="#">{{link}}</a>
                        <a class="nav-link">
                            <Button content="donate" type="normal"/>
                        </a>
                    </div>
                </div>
            </div>
        </nav>
</template>
<script>

import Button from './../Button.vue' 

export default {
    name:'Menu',
    props:['navbar'],
    components:
    {
        Button,
    }
    
}
</script>
<style lang="scss" scoped>
@import '../../assets/scss/_vars.scss';
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
    .active-link
    {
        color: $main-yellow; 
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