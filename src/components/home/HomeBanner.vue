<template>
    <div class="banner_container">
    <div class="container">
      <div class="d-md-flex justify-content-center">
        <div class="bannerbox1">
          <div>
            <h1 class="mb-4">Sneakers that you love</h1>
            <p class="fs-5 mb-4">Check out our various variety of sneakers and get a pair that you love</p>
            <button type="button" class="btn btn-dark btn-lg">Check Out</button>
          </div>
        </div>
        <div class="bannerbox2">
          <img src="../images/shoe.png" alt="shoe" width="700px" height="500px" class="img-fluid">
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.banner{
    height: 500px;
}
.banner_container{
    background-color: wheat;
}

.bannerbox1{
    flex-basis: 50%;
    padding: 20px;
    justify-content: center;
    align-items: center;
    display: flex;
}

.bannerbox2{
    flex-basis: 50%;
    padding: 20px;
    margin: auto;
    justify-content: center;
    display: flex;
}

.bannerbox1 div h1{
    font-size: 55px;
    font-weight: 750;
}
</style>

<script lang="ts">
export default {
    name:'HomeBanner',
}
</script>