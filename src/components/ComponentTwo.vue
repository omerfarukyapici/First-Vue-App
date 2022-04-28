<template>
  <div class="CompTwoDiv">
    <h3>This is Component Two.</h3>
    <p>This is Copmponent Two prop -> ({{ compTwoName }})</p>
    <!-- <p> {{compTwoAge}} </p> -->
  </div>
</template>

<script>
export default {
  name: "ComponentTwo",
  props: {
    compTwoName: String,
    /* compTwoAge: number */
  },
};
</script>

<style>
.CompTwoDiv {
    background-color: cadetblue;
    padding: 1rem;
}
h3 {
  background-color: red;
  color: black;
}
p {
  background-color: black;
  color: white;
}
</style>