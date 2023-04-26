<template>
    <div class="card mb-4 h-100" style="max-width:300px;">
              <div class="cardimage"><a href="single_product.html"><img class="card-img-top p-3"
                    src="./home images/airforce1.png" alt="Card image cap"></a></div>
              <div class="card-body d-flex flex-column justify-content-between">
                <h5 class="card-title">Nike Air Force 1</h5>
                <div class="mb-3">
                  <img src="./home images/star.svg" alt="" width="17px" height="17px">
                  <img src="./home images/star.svg" alt="" width="17px" height="17px">
                  <img src="./home images/star.svg" alt="" width="17px" height="17px">
                  <img src="./home images/star.svg" alt="" width="17px" height="17px">
                  <img src="./home images/star.svg" alt="" width="17px" height="17px">
                </div>
                <p class="card-text fs-5">$100</p>
                <div class="d-flex flex-column flex-lg-row flex-md-row justify-content-between gap-2 mt-auto">
                  <a href="#" class="btn btn-outline-dark"   @click ="onclick()">Add to Cart</a>
                  <a href="#" class="btn btn-outline-dark">Add to Wishlist</a>
                </div>
              </div>
            </div>
</template>


<style>
.cardimage{
    background-color: wheat;
}
</style>

<script lang="ts">
export default {
    name:'Card',


    methods :{
      onclick()
      {
        alert ("hi ");
        
      }

    }
}
</script>