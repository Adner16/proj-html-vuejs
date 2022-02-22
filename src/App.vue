<template>
  <div id="app">
    <Header :items='links'/>
    <Jumbotron />
    <Main />
    

  </div>
</template>

<script>
import Header from './components/Header.vue';
import Jumbotron from './components/Jumbotron.vue';
import Main from './components/Main.vue';


export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    Main,
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
      }
  
  }
}
 
</script>

<style scoped lang="scss">
#app {
 
  
 
}
@import'~bootstrap/dist/css/bootstrap.css'
</style>
