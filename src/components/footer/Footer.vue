<template>
    <div class="footer text-center">
        <p>
            &copy;Copyrigth 2012 - 2020 AVADA THEME BY THEME FUSION | ALL RIGHTS RESERVED | POWERED BY WORDPRESS
        </p>
        <div class="social d-flex justify-content-center align-items-center">
            <i class="fab fa-facebook-f fa-2x"></i>
            <i class="fab fa-instagram fa-2x"></i>
            <i class="fab fa-twitter fa-2x"></i>
            <i class="fab fa-youtube fa-2x"></i>
        </div>
    </div>
</template>
<script>
export default {
    name:'Footer',
}
</script>
<style lang="scss" scoped>

@import '../../assets/scss/_vars.scss'; 

.footer
{
    background-color: $footer-gray;
    padding: 30px 0;
    font-size: 10px;
    color: $footer-text;
}

.social
{
    i{
        width: 50px;
        height: 50px;
        background-color: $menu-color;
        color: $main-yellow;
        border-radius: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 0 10px;
    }
    i:hover{
        color:$main-red;
    }
}
</style>