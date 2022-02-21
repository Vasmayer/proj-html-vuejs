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
import Header from './components/Header.vue' 
import Main from './components/Main.vue' 
import Footer from './components/Footer.vue' 

import 'bootstrap';

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
