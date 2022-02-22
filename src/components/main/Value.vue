<template>
     <div class="col-12 col-md-3 text-center">
        <i class="fa-2x c-yellow" :class="textIcon"></i>
        <div class="pb-3">{{intestation}}</div>
        <div class="fs-13 pb-3">
            {{text}} 
        </div>
        <Button content="learn more" type="normal"/>
    </div>
</template>

<script>

import Button from './../Button.vue' 

export default {
    name:'Values',
    props:['textIcon','intestation','text'],
    components:
    {
        Button,
    }

}
</script>

<style lang="scss" scoped>
@import '../../assets/scss/_vars.scss'; 

.c-yellow{
    color: $main-yellow;
}
.fs-13
{
    font-size: 13px;
}
</style>