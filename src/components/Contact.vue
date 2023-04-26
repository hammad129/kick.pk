<template>

<form @submit.prevent="submit">
   <div class="form-group">
      <label class="inputa-label" for="exampleInputEmail1"
         >Email address</label
         >
      <input
         type="email"
         class="form-control inputa"
         id="exampleInputEmail1"
         placeholder="Enter email"
         required
         v-model="email"
         />
   </div>
   <div class="form-group">
      <label class="inputa-label" for="exampleInputPassword1"
         >Phone number</label
         >
      <input
         type="number"
         class="form-control inputa"
         id="exampleInputPassword1"
         placeholder="Phone"
         v-model="phone"
         />
   </div>
   <div class="form-group">
      <label class="inputa-label" for="exampleInputPassword1"
         >Information</label
         >
      <textarea
         class="form-control inputa"
         aria-label="With textarea"
         v-model="information"
         ></textarea>
   </div>
   <button
      type="submit"
      style="font-weight:600; padding: .8125rem 1.25rem"
      class="btn btn-primary"
      >
   Submit
   </button>
</form>
</template>



<script lang="ts">
export default {
    name:'Contact',

    data() {
    return {
      email:"",
      phone:"",
      information:"",
    };
  },
  methods: {
    submit() 
    {
            const data = JSON.stringify({
            Email: this.email,
            Phone: this.phone,
            Information: this.information})

            console.log(data)
      
    },
  },
   
}
</script>