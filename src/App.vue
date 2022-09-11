<template>
  
<v-app>
<Header/>
<Searchbar/>
<Footer/>  

</v-app>


</template>

<script>
import Footer from './components/Footer.vue';
import Header from './components/Header.vue';
import Searchbar from './components/Searchbar.vue';


export default {
  name: 'App',
  components: {
    Header, Footer, Searchbar
  }
}
  
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.search-text-container {
    width: 50%;
    display: inline-block;
    margin: 10px;
  }
  .search-bar {
    border: 1px solid #ccc;
    outline: 0;
    border-radius: 5px;
    width: 50%;
    padding: 0.5rem;
  }
  .search-bar:focus {
    box-shadow: 0 0 15px 5px #b0e0ee;
    border: 2px solid #bebede;
  }
</style>
