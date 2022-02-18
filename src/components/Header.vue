<template>
    <div>
            <Nav :navbar="navbar"/>
    </div>
</template>

<script>
import Nav from './Nav.vue' 

export default {
    name:'Header',
    props:['navbar'],
    components: {
      Nav,
    }
}
</script>

<style lang="scss" scoped>

</style>