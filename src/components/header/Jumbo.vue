<template>
     <div class="flex-grow-1 position-relative">
            <div class="position-absolute top-50 start-50 translate-middle text-light">
              <h1 class="text-center">{{titleJumbo}}</h1>
              <p>{{paragraphJumbo}}</p>
              <div class="text-center">
                <Button content="our mission" type="outlined-white"/>
                <Button content="donate now" type="outlined-yellow" class="ms-3"/>
              </div>
            </div>
        </div>
</template>
<script>
import Button from './../Button.vue' 

export default {
    name:'Jumbo',
    props:['titleJumbo','paragraphJumbo'],
    components:
    {
        Button,
    }
}
</script>
<style lang="scss" scoped>
p        
{
    font-size: 13px;
}

</style>