<template>
  <p v-if="age > 35">{{msg}}</p>
  <p v-else>You must be above 35 to review this message!</p>
</template>

<script>
export default {
      name: "Greeting",
       props:['age'],
  data() {
    return {
      msg: "Hello world!!!",
     
    };
  },
};

</script>
<style  >
*{
    background-color: black;
    color:chartreuse;
}
</style>

