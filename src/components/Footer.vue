<template>
     <!-- Footer -->
     <footer>
      <div class="container py-5">
        <div class="row py-4">
          <div class="col-lg-4 col-md-6 mb-4 mb-lg-0">
            <h4 class="font-weight-bold">Kicks.pk</h4>
            <p class="font-italic text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt.</p>
            <ul class="list-inline mt-4">
              <li class="list-inline-item"><a href="#" target="_blank" title="twitter"><img src="./icons/twitter.svg" alt=""></a></li>
              <li class="list-inline-item"><a href="#" target="_blank" title="facebook"><img src="./icons/facebook.svg" alt=""></a></li>
              <li class="list-inline-item"><a href="#" target="_blank" title="instagram"><img src="./icons/instagram.svg" alt=""></a></li>
            </ul>
          </div>
          <div class="col-lg-2 col-md-6 mb-4 mb-lg-0">
            <h6 class="text-uppercase font-weight-bold mb-4">Shop</h6>
            <ul class="list-unstyled mb-0">
              <li class="mb-2"><a href="#" class="text-muted text-decoration-none">For Women</a></li>
              <li class="mb-2"><a href="#" class="text-muted text-decoration-none">For Men</a></li>
              <li class="mb-2"><a href="#" class="text-muted text-decoration-none">For Kids</a></li>
              <li class="mb-2"><a href="#" class="text-muted text-decoration-none">Our Blog</a></li>
            </ul>
          </div>
          <div class="col-lg-2 col-md-6 mb-4 mb-lg-0">
            <h6 class="text-uppercase font-weight-bold mb-4">Company</h6>
            <ul class="list-unstyled mb-0">
              <li class="mb-2"><a href="#" class="text-muted text-decoration-none">Login</a></li>
              <li class="mb-2"><a href="#" class="text-muted text-decoration-none">Register</a></li>
              <li class="mb-2"><a href="#" class="text-muted text-decoration-none">Wishlist</a></li>
              <li class="mb-2"><a href="#" class="text-muted text-decoration-none">Our Products</a></li>
            </ul>
          </div>
          <div class="col-lg-4 col-md-6 mb-lg-0">
            <h6 class="text-uppercase font-weight-bold mb-4">Newsletter</h6>
            <p class="text-muted mb-4">Lorem ipsum dolor sit amet, consectetur adipisicing elit. At itaque temporibus.</p>
            <div class="p-1 rounded border">
              <div class="input-group">
                <input type="email" placeholder="Enter your email address" aria-describedby="button-addon1" class="form-control border-0 shadow-0 rounded">
                <div class="input-group-append">
                  <button id="button-addon1" type="submit" class="btn btn-link"><i class="fa fa-paper-plane"></i></button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
  
      <!-- Copyrights -->
      <div class="copyright">
        <div class="container text-center">
          <p class="text-muted mb-0 py-2">© 2019 Kicks.pk All rights reserved.</p>
        </div>
      </div>
    </footer>
    <!-- End -->
</template>

<script lang="ts">
export default {
    name:'Footer',
}
</script>

<style>
i {
    color: black;
  }

  footer{
    background-color: rgb(247, 205, 127);
    margin-top: 100px;
  }

  .copyright{
    background-color: rgb(248, 218, 163);
    padding: 20px 0px 20px 0px;
  }

 
</style>