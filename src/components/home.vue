<template>
    <Navbar />
    <!-- Banner -->
    <HomeBanner />
    <!-- Hot Products Section -->
    <HotProducts />
    <!-- Featured Products Section -->
    <FeaturedProducts />
    <!-- Reviews Section -->
    <ReviewSection />
    <Footer />
  </template>
  
  <script lang="ts">
  import Navbar from './Navbar.vue'
  import Footer from './Footer.vue';
  import HotProducts from './home/HotProducts.vue';
  import HomeBanner from './home/HomeBanner.vue'
  import FeaturedProducts from './home/FeaturedProducts.vue';
  import ReviewSection from './home/ReviewSection.vue';
  
  export default {
    name:'App',
    components:{
      Navbar,
      Footer,
      HotProducts,
      HomeBanner,
      FeaturedProducts,
      ReviewSection,
  }
  }
  </script>
  
  <style>
  *{
      margin: 0%;
  }
  
  </style>