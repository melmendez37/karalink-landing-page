<template>
  <NavBar/>
  <Jumbotron/>
  <JumbotronTwo/>
  <JumbotronThree/>
  <Cards/>
  <Footer/>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Jumbotron from './components/Jumbotron.vue'
import Footer from './components/Footer.vue'
import JumbotronTwo from './components/JumbotronTwo.vue'
import JumbotronThree from './components/JumbotronThree.vue'
import Cards from './components/Cards.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Jumbotron,
    JumbotronTwo,
    JumbotronThree,
    Cards,
    Footer,
  }
}
</script>

<style>
#app {
  font-family: 'Trebuchet MS', Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
