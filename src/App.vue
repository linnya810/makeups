<template>
  <Navbar/>
  <router-view></router-view>
  <Footer/>
</template>

<script>
import Navbar from './components/homeNavbar.vue'
import Footer from './components/homeFooter.vue'
export default {

  components:{Navbar,Footer},
  data(){
    return{

    }
  }
}
</script>

<style>
li{
  list-style: none;
}
</style>
