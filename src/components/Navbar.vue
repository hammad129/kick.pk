<template>
    <div class="nav_container">
<nav class="navbar navbar-expand-lg">
    <div class="container-fluid">
      <a class="navbar-brand " href="home.html">Kicks.pk</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#/" ></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="pr">Product</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about_us.html">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact_us.html">Contact Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Admin Dashboard</a>
          </li>
        </ul>
        <div class="d-md-flex gap-4 align-items-center justify-content-between">   
            <form class="searchbar" role="search">
            <input class="bg-transparent border-0 shadow-none" type="search" name="q" placeholder="Search">
            <button class="bg-transparent border-0"><img src="./icons/search.svg" alt="search" width="25px" height="25px"></button>
            </form>
            <a class="my-2" href="customer_dashboard.html"><img title="Customer Dashboard" src="./icons/user.svg" alt="userProfile" width="32px" height="32px"></a>
            <a class="my-2" href="cart.html"><img title="Cart" src="./icons/cart.svg" alt="cart" width="32px" height="32px"></a>
            </div>
      </div>
    </div>
  </nav>
</div>
</template>

<script lang="ts">
import App from '../App.vue'

export default {
    name: 'Navbar',


}
</script>

<style>
.searchbar
 {
    background-color:white;
    border-radius: 20px;
    padding: 5px 10px;
    width: 300px;
    margin-bottom: 2px;
 }
 .searchbar input{
    outline: 0px;
    width: 85%;
 }

 .nav_container{
    background-color: rgb(245, 213, 155);
 }

 .logo
 {
    font-family: "Gill Sans", sans-serif;
    font-weight: bolder;
 }

.nav_option{
    font-family: "Gill Sans", sans-serif;
}
 
</style>