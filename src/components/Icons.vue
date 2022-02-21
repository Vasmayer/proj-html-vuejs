<template>
    <div class="pb-5">
        <i class="fa-2x" :class="classIcon">&nbsp;{{number}}</i>
        <div>{{textInfo}}</div>
    </div>
</template>

<script>
export default {
    name:'icons',
    props:['classIcon','number','textInfo'],
    
}
</script>

<style lang="scss" scoped>

</style>