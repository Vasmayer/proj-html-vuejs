<template>
<div class="values d-flex justify-content-center align-items-center flex-column text-light">

            <div>OUR VALUES</div>
            <YellowLine class="my-3"/>
            <p class="mb-5 fs-13">Think Big. Act Bigger.</p>
            <div class="container">
                <div class="row">
                    <Value text-icon="fa-solid fa-droplet" intestation="Clean water" text="Lorem ipsum dolor sit amet consectetur adipisicing elit. "/>
                    <Value text-icon="fa-solid fa-stethoscope" intestation="Vaccinations" text="Lorem ipsum dolor sit amet consectetur adipisicing elit. "/>
                    <Value text-icon="fa-solid fa-graduation-cap" intestation="Education" text="Lorem ipsum dolor sit amet consectetur adipisicing elit. "/>
                    <Value text-icon="fa-brands fa-pagelines" intestation="Farming" text="Lorem ipsum dolor sit amet consectetur adipisicing elit. "/>
                </div>
            </div>
</div>
</template>
<script>
import YellowLine from './../Line.vue' 
import Value from './Value.vue' 

export default {
    name:'Values',
    components:
    {
        YellowLine,
        Value,
    }
}
</script>
<style lang="scss" scoped>
    .values
    {
        height: 600px;
        background-image: url('../../assets/images/home-content-bg-2.jpg');
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;

        .fs-13
        {
             font-size: 13px;
        }
    }
     
</style>