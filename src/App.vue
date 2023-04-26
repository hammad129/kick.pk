<template>
  
  <Contact/>
</template>

<script lang="ts">
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue';
import HotProducts from './components/home/HotProducts.vue';
import HomeBanner from './components/home/HomeBanner.vue'
import FeaturedProducts from './components/home/FeaturedProducts.vue';
import ReviewSection from './components/home/ReviewSection.vue';
import home from './components/home.vue'; 
import cart from './components/cart/cart.vue';
import Contact from './components/Contact.vue';

export default {
  name:'App',
  components:{
    Navbar,
    Footer,
    HotProducts,
    HomeBanner,
    FeaturedProducts,
    ReviewSection,
    home,
    cart ,
    Contact,
    
  }
}
</script>

<style>
*{
    margin: 0%;
}

</style>