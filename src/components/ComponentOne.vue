<template>
  <div class="CompOneDiv">
    <div class="CompOneDivMain">
      <h3>This is Component One.</h3>
      <p>This is Component One prop (string) -> ({{ compOneName }})</p>
      <!-- <p> {{compOneAge}} </p> -->
    </div>
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
  padding: 1rem;
  color: black;
  display: flex;
  justify-content: center;
}
.CompOneDivMain {
  width: 1200px;
  background-color: rgb(196, 241, 247);
  padding: 1rem;
}
h3 {
  padding: 0rem 0rem 1rem 0rem; 
}
</style>