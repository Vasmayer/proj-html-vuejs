<template>
    <div>
        <div class="container-fluid">
            <div class="row">
                <div class="col-12 col-md-8 p-5 d-flex justify-content-center align-items-center">
                    <Moments />
                </div>
                <div class="col-12 col-md-4 bg-info text-light p-5 fs-13 d-flex justify-content-center align-items-center">
                    <div class="info">
                        <Icon class-icon="far fa-heart" number="2032" text-info="Volunteers wordwide"/>
                        <Icon class-icon="fas fa-globe" number="132" text-info="Active projects"/>
                        <Icon class-icon="fas fa-dollar-sign" number="3.8M" text-info="Donated"/>
                    </div>
                </div>
            </div>
        </div>
        <Values />
        <Causes />
        <div class="all-causes d-flex justify-content-center align-items-center text-light my-5">
            <h6 class="fs-13 m-0">VIEW AL OUR CAUSES</h6>
        </div>
        <Articles />
        <Change />
        <div class="logo d-flex justify-content-center align-items-center p-3">
             <img :src="require('../../assets/images/avada-charity-mobile-logo-retina.png')" alt="logo avada" class="img-fluid">
        </div>
    </div>
</template>
<script>
import Icon from './Icons.vue' 
import Moments from './Moments.vue'
import Values from './Values.vue'  
import Causes from './Causes.vue' 
import Articles from './Articles.vue' 
import Change from './Change.vue' 


export default {
    name:'Main',
    components:
    {
        Icon,
        Moments,
        Values,
        Causes,
        Articles,
        Change,
    }
}
</script>
<style lang="scss" scoped>

@import '../../assets/scss/_vars.scss'; 


    .bg-info
    {
        background-image: url('../../assets/images/home-content-bg-1.jpg');
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
    }
    .all-causes
    {
        background-color: $main-red;
        padding: 30px 0;
    }
    .logo
    {
        img{
            transform: scale(0.5);
        }
    }
</style>