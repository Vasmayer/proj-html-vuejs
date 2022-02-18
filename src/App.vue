<template>
  <div>
    <header>
     <Header :navbar="navbar" />
    </header>
    <main></main>
    <footer></footer>
  </div>
</template>

<script>
import Header from './components/Header.vue' 
import 'bootstrap';

export default {
  name: 'App',
  components: {
   Header,
  },
  data()
  {
    return{
      navbar:['home','mission','causes','journal']
    }
  }
}
</script>
<style lang="scss">

@import './assets/scss/index.scss';

</style>
