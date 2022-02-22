<template>
    <div class="causes d-flex justify-content-center align-items-center flex-column">
            <div class="pt-5">RECENT CAUSES</div>
            <YellowLine class="my-3"/>
            <p>We run projects in over 30 coutries in 5 continents</p>
            <div class="container">
                <div class="row">
                    <div class="col-12 col-md-3">
                        <img class="img-fluid" :src="require('../../assets/images/avada-charity-fair-trade-featured-400x300.jpg')" alt="Fair Trade">
                    </div>
                    <div class="col-12 col-md-3">
                        <img class="img-fluid" :src="require('../../assets/images/avada-charity-shelter-featured-400x300.jpg')" alt="Fair Trade">
                    </div>
                    <div class="col-12 col-md-3">
                        <img class="img-fluid" :src="require('../../assets/images/avada-charity-farming-featured-400x300.jpg')" alt="Fair Trade">
                    </div>
                    <div class="col-12 col-md-3">
                        <img class="img-fluid" :src="require('../../assets/images/avada-charity-vaccines-featured-400x300.jpg')" alt="Fair Trade">
                    </div>
                </div>
            </div>
    </div>
</template>
<script>
import YellowLine from './../Line.vue' 

export default {
    name:'Causes',
    components:
    {
        YellowLine,
    }
}
</script>
<style lang="scss" scoped>

</style>