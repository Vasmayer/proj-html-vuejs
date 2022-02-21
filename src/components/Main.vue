<template>
    <div>
        <div class="jumbo container-fluid">
            <div class="row">
                <div class="col-12 col-md-8 p-5 d-flex justify-content-center align-items-center">
                    <div>
                        <h3>EVERY MOMENT COUNTS</h3>
                        <YellowLine class="my-3"/>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi commodi voluptate sed asperiores ut dolor cupiditate magnam dolorum</p>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Temporibus nulla voluptatibus sunt ipsum quidem eos. Qui tempora architecto aperiam, sit nihil, hic quas inventore distinctio assumenda enim vel necessitatibus eum.</p>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet, dolores.</p>
                        <Button content="our mission" type="normal"/>
                    </div>
                </div>
                <div class="col-12 col-md-4 bg-home-content text-light p-5 fs-13 d-flex justify-content-center align-items-center">
                    <div>
                        <Icon class-icon="far fa-heart" number="2032" text-info="Volunteers wordwide"/>
                        <Icon class-icon="fas fa-globe" number="132" text-info="Active projects"/>
                        <Icon class-icon="fas fa-dollar-sign" number="3.8M" text-info="Donated"/>

                    </div>
                </div>
            </div>
        </div>
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
        <div class="causes d-flex justify-content-center align-items-center flex-column">
            <div class="pt-5">RECENT CAUSES</div>
            <YellowLine class="my-3"/>
            <p>We run projects in over 30 coutries in 5 continents</p>
            <div class="container">
                <div class="row">
                    <div class="col-12 col-md-3">
                        <img class="img-fluid" :src="require('../assets/images/avada-charity-fair-trade-featured-400x300.jpg')" alt="Fair Trade">
                    </div>
                    <div class="col-12 col-md-3">
                        <img class="img-fluid" :src="require('../assets/images/avada-charity-shelter-featured-400x300.jpg')" alt="Fair Trade">
                    </div>
                    <div class="col-12 col-md-3">
                        <img class="img-fluid" :src="require('../assets/images/avada-charity-farming-featured-400x300.jpg')" alt="Fair Trade">
                    </div>
                    <div class="col-12 col-md-3">
                        <img class="img-fluid" :src="require('../assets/images/avada-charity-vaccines-featured-400x300.jpg')" alt="Fair Trade">
                    </div>
                </div>
            </div>
        </div>
        <div class="all-causes d-flex justify-content-center align-items-center text-light my-5">
            <h6 class="fs-13 m-0">VIEW AL OUR CAUSES</h6>
        </div>
        <div class="articles d-flex justify-content-center align-items-center flex-column">
            <div>LATEST ARTICLES</div>
            <YellowLine class="my-3"/>
            <p class="mb-5 fs-13">Together we make all the difference</p>
            <div class="container">
                <div class="row">
                    <div class="col-6 h-100">
                        <article class="border">
                            <img :src="require('../assets/images/photo-1444213007800-cff19e1677ac-600x450.jpg')" alt="article" class="img-fluid w-100">
                            <div class="p-3">
                                <h6>Understating community complexities</h6>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                        </article>
                    </div>
                    <div class="col-6">
                         <article class="d-flex justify-content-center align-items-center h-25">
                            <img :src="require('../assets/images/photo-1444664597500-035db93e2323-177x142.jpg')" alt="article" class="img-fluid img-small">
                            <div class="fs-13 p-3">
                                <h6>The uman story iuniquess</h6>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                        </article>
                        <article class="d-flex justify-content-center align-items-center h-25">
                            <img :src="require('../assets/images/photo-1447430617419-95715602278e-177x142.jpg')" alt="article" class="img-fluid img-small">
                            <div class="fs-13 p-3">
                                <h6>Sustainable trade tactis</h6>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                        </article>
                        <article class="d-flex justify-content-center align-items-center h-25">
                            <img :src="require('../assets/images/photo-1460230525622-630fe3294cd7-177x142.jpg')" alt="article" class="img-fluid img-small">
                            <div class="fs-13 p-3">
                                <h6>Farmers make difference</h6>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            </div>
                        </article>
                        <article class="d-flex justify-content-center align-items-center h-25">
                            <img :src="require('../assets/images/photo-1460600421604-5e138c208b9c-177x142.jpg')" alt="article" class="img-fluid img-small">
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
        <div class="change d-flex justify-content-center align-items-center flex-column text-light">
                <div>CHANGE A LIFE TODAY</div>
                <YellowLine class="my-3"/>
                <p class="fs-13">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut sed natus mollitia eligendi, non ex iure animi expedita est consectetur a deserunt totam itaque ab autem<br>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut sed natus mollitia eligendi, non ex iure animi expedita est consectetur a deserunt totam itaque ab autem</p>
                <div class="text-center">
                    <Button content="our mission" type="outlined-white"/>
                    <Button content="donate now" type="outlined-white" class="ms-3"/>
                </div>
        </div>
        <div class="logo d-flex justify-content-center align-items-center p-3">
             <img :src="require('../assets/images/avada-charity-mobile-logo-retina.png')" alt="logo avada" class="img-fluid">
        </div>
        <div>
            <Footer />
        </div>
    </div>
</template>
<script>
import YellowLine from './Line.vue' 
import Button from './Button.vue' 
import Icon from './Icons.vue' 
import Value from './Value.vue' 
import Footer from './Footer.vue' 

export default {
    name:'Main',
    components:
    {
        YellowLine,
        Button,
        Icon,
        Value,
        Footer
    }
}
</script>
<style lang="scss" scoped>

@import '../assets/scss/_vars.scss'; 


    .bg-home-content
    {
        background-image: url('../assets/images/home-content-bg-1.jpg');
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
    }
    .fs-13
    {
        font-size: 13px;
    }
    .values
    {
        height: 600px;
        background-image: url('../assets/images/home-content-bg-2.jpg');
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;

    }
    .change
    {
        height: 400px;
        background-image: url('../assets/images/home-footer.jpg');
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
    }
    .all-causes
    {
        background-color: $main-red;
        padding: 30px 0;
    }

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
    }
    .logo
    {
        img{
            transform: scale(0.5);
        }
    }
</style>