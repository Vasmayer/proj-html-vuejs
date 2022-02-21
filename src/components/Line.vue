<template>
   <div class="yellow-line">
     
   </div> 
</template>
<script>
export default {
    name:'YellowLine',
}
</script>
<style lang="scss" scoped>
@import '../assets/scss/_vars.scss'; 

.yellow-line
{
    width: 200px;
    height: 2px;
    background-color: $main-yellow;
}
</style>