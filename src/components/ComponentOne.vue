<template>
  <div class="CompOneDiv">
    <h3>This is Component One.</h3>
    <p>This is Component One prop (string) -> ({{ compOneName }})</p>
    <!-- <p> {{compOneAge}} </p> -->
  </div>
</template>

<script>
export default {
  name: "ComponentOne",
  props: {
    compOneName: String,
    /* compOneAge: number */
  },
};
</script>

<style>
.CompOneDiv {
    background-color: aqua;
    padding: 1rem;
}
h3 {
  background-color: black;
  color: red;
}
p {
  background-color: grey;
  color: black;
}
</style>