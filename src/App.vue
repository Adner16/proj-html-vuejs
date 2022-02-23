<template>
  <div id="app">
    <Header :items='links'/>
    <Jumbotron />
    <Main />
    <Footer :items='footerLinks'/>
  </div>
</template>

<script>
import Header from './components/Header';
import Jumbotron from './components/Jumbotron';
import Main from './components/Main';
import Footer from './components/Footer';


export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    Main,
    Footer,
  },
    data(){
      return{
        links:[
          'home',
          'about',
          'services',
          'showcase',
          'blog',
          'contact',
        ],
        footerLinks:[
          {name:'Careers', site:'#'},
          {name:'News', site:'#'},
          {name:'Terms of use', site:'#'},
          {name:'Privacy project', site:'#'},
          {name:'About', site:'#'},
          {name:'Contact', site:'#'},
        ]
      }
  
  }
}
 
</script>

<style scoped lang="scss">
#app {
 
  
 
}
@import'~bootstrap/dist/css/bootstrap.css'
</style>
