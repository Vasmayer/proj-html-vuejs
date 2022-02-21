<template>
<div class="moments">
    <h3>EVERY MOMENT COUNTS</h3>
    <YellowLine class="my-3"/>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi commodi voluptate sed asperiores ut dolor cupiditate magnam dolorum</p>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Temporibus nulla voluptatibus sunt ipsum quidem eos. Qui tempora architecto aperiam, sit nihil, hic quas inventore distinctio assumenda enim vel necessitatibus eum.</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet, dolores.</p>  
    <Button content="our mission" type="normal"/>
</div>
</template>

<script>
import YellowLine from './Line.vue' 
import Button from './Button.vue' 

export default {
    name:'Moments',
    components:
    {
        YellowLine,
        Button,
    }
}
</script>

<style lang="scss" scoped>

</style>