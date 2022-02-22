<template>
  <div>
    <header>
     <Header :navbar="navbar" />
    </header>
    <main>
      <Main />
    </main>
    <footer>
      <Footer />
    </footer>
  </div>
</template>

<script>
import Header from './components/header/Header.vue' 
import Main from './components/main/Main.vue' 
import Footer from './components/footer/Footer.vue' 



export default {
  name: 'App',
  components: {
   Header,
   Main,
   Footer,
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
