<template>
    <div class="container px-4">
    <div class="d-flex flex-column">
      <div>
        <h1 class="my-5">Reviews</h1>
        <div class="row">
          <div class="col-lg-6 col-md-6">
            <ReviewCard />
          </div>
          <div class="col-lg-6 col-md-6">
            <ReviewCard />
          </div>
        </div>
        <div class="row">
          <div class="col-lg-6 col-md-6">
            <ReviewCard />
          </div>
          <div class="col-lg-6 col-md-6">
            <ReviewCard />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import ReviewCard from './ReviewCard.vue';

export default {
    name:'ReviewSection',
    components:{
        ReviewCard,
    }
}
</script>