<template>
    <Header />
    <router-view/>
    <Footer />
   <!-- <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> -->
</template>

<script>
import Header from './components/Header'
import Footer from './components/Footer'


export default {
  name:'App',
  components:{
    Header,
    Footer
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
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
