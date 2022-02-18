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
    margin: 0 5px;
}
.normal
{
    color: $menu-color;
    background-color:$button;
    border:1px solid $button;
}
.outlined-yellow
{
    color: $button;
     border:1px solid $button;
     background-color: transparent;
}
.outlined-white
{
     color: $menu-color;
     border:1px solid $menu-color;
     background-color: transparent;
}

</style>