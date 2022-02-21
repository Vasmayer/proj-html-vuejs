<template>
        <button :class="type">
            {{content}}
        </button>
</template>
<script>
export default {
    name:'Button',
    props:['content','type'],
    
}
</script>
<style lang="scss" scoped>

@import '../assets/scss/_vars.scss'; 

button
{
    text-transform: uppercase;
  
    padding: 4px 15px;
    font-size: 10px;
}
.normal
{
    color: $menu-color;
    background-color:$main-yellow;
    border:1px solid $main-yellow;
}
.normal-red
{
    color: $menu-color;
    background-color:$main-red;
    border:1px solid $main-red;
    width: 100%;
}
.outlined-yellow
{
     color: $main-yellow;
     border:1px solid $main-yellow;
     background-color: transparent;
}
.outlined-white
{
     color: $menu-color;
     border:1px solid $menu-color;
     background-color: transparent;
}

</style>