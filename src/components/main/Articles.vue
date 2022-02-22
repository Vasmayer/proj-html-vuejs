<template>
    <div class="articles d-flex justify-content-center align-items-center flex-column">
            <div>LATEST ARTICLES</div>
            <YellowLine class="my-3"/>
            <p class="mb-5 fs-13">Together we make all the difference</p>
            <div class="container">
                <div class="row">
                    <div class="col-6 h-100">
                        <article class="border">
                            <img :src="require('../../assets/images/photo-1444213007800-cff19e1677ac-600x450.jpg')" alt="article" class="img-fluid w-100">
                            <div class="p-3">
                                <h6>Understating community complexities</h6>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                        </article>
                    </div>
                    <div class="col-6">
                         <article class="d-flex justify-content-center align-items-center h-25">
                            <img :src="require('../../assets/images/photo-1444664597500-035db93e2323-177x142.jpg')" alt="article" class="img-fluid img-small">
                            <div class="fs-13 p-3">
                                <h6>The uman story iuniquess</h6>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                        </article>
                        <article class="d-flex justify-content-center align-items-center h-25">
                            <img :src="require('../../assets/images/photo-1447430617419-95715602278e-177x142.jpg')" alt="article" class="img-fluid img-small">
                            <div class="fs-13 p-3">
                                <h6>Sustainable trade tactis</h6>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                        </article>
                        <article class="d-flex justify-content-center align-items-center h-25">
                            <img :src="require('../../assets/images/photo-1460230525622-630fe3294cd7-177x142.jpg')" alt="article" class="img-fluid img-small">
                            <div class="fs-13 p-3">
                                <h6>Farmers make difference</h6>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                        </article>
                        <article class="d-flex justify-content-center align-items-center h-25">
                            <img :src="require('../../assets/images/photo-1460600421604-5e138c208b9c-177x142.jpg')" alt="article" class="img-fluid img-small">
                            <div class="fs-13 p-3">
                                <h6>Meeting remote triber in Perù</h6>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                        </article>
                    </div>
                    <div class="col-12 my-3">
                        <Button content="view all our articles" type="normal-red"/>
                    </div>
                </div>
            </div>
        </div>
</template>
<script>
import Button from './../Button.vue' 
import YellowLine from './../Line.vue' 

export default {
    name:"Articles",
    components:
    {
        Button,
        YellowLine,
    }
}
</script>
<style lang="scss" scoped>
@import '../../assets/scss/_vars.scss'; 

    .articles
    {  
        h6{
            color: $main-yellow;
        }
        .img-small
        {
            width: 100px;
            height: 100px;
        }
        .fs-13
        {
           font-size: 13px;
        }
    }
</style>