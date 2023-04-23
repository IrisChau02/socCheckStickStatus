<template>
  <nav aria-label="breadcrumb">
    <ol class="breadcrumb">
      <li class="breadcrumb-item"><a href="/">Home</a></li>
      <li class="breadcrumb-item active" aria-current="page">Profile</li>
    </ol>
  </nav>

  <button type="button" class="btn btn-primary">Here is the profile page</button>

</template>

<script>
//import { ref, onMounted, computed } from "vue";

export default {

  name: 'ProfileView',
  props: {
    msg: String
  },
  setup() {
    
    return {//to make the instance properties and instance methods visible 
 
    };

  },

};

</script>
