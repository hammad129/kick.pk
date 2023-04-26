<template>
    <div class="container px-4">
    <div class="d-flex flex-column">
      <div>
        <h1 class="my-5">Featured Products</h1>
        <div class="row gy-3">
          <div class="col-lg-3 col-md-6 col-6">
            <Card />
          </div>
          <div class="col-lg-3 col-md-6 col-6">
            <Card />
          </div>
          <div class="col-lg-3 col-md-6 col-6">
            <Card />
          </div>
          <div class="col-lg-3 col-md-6 col-6">
            <Card />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Card from './Card.vue'

export default {
    name:'FeaturedProducts',
    components: {
        Card,
    }
}
</script>