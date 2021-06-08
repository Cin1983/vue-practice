<template>
<h3>Fawaka</h3>
<button type="button" @click="age++"> Update Age </button>
<greeting/>
<user :age="age"/>
</template>

<script>
import Greeting from "./components/Greeting.vue";
import User from "./components/user.vue";

export default {
  name: "App",
  components: {
    Greeting,
    User
  },
  data(){
    return{
     age:38 
    }
  }
};
</script>
