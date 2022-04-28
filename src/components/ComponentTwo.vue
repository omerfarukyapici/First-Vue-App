<template>
  <div class="CompTwoDiv">
    <div class="CompTwoDivMain">
      <h3>This is Component Two.</h3>
      <p>This is Copmponent Two prop -> ({{ compTwoName }})</p>
      <!-- <p> {{compTwoAge}} </p> -->
    </div>
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
  padding: 1rem;
  color: black;
  display: flex;
  justify-content: center;
}
.CompTwoDivMain {
  width: 1200px;
  background-color: rgb(244, 176, 247);
  padding: 1rem;
}
</style>