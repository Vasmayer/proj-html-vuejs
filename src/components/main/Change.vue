<template>
    <div class="change d-flex justify-content-center align-items-center flex-column text-light">
                <div>CHANGE A LIFE TODAY</div>
                <YellowLine class="my-3"/>
                <p class="fs-13">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut sed natus mollitia eligendi, non ex iure animi expedita est consectetur a deserunt totam itaque ab autem<br>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut sed natus mollitia eligendi, non ex iure animi expedita est consectetur a deserunt totam itaque ab autem</p>
                <div class="text-center">
                    <Button content="our mission" type="outlined-white"/>
                    <Button content="donate now" type="outlined-white" class="ms-3"/>
                </div>
    </div>
</template>
<script>
import Button from './../Button.vue' 
import YellowLine from './../Line.vue' 

export default {
    name:'Change',
    components:
    {
        Button,
        YellowLine,
    }
}
</script>
<style lang="scss" scoped>
    .change
    {
        height: 400px;
        background-image: url('../../assets/images/home-footer.jpg');
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
    }
    .fs-13
    {
        font-size: 13px;
    }
</style>