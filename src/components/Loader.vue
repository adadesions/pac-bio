x<template>
  <div class="loader container">
    <div id="spin-1" class="item spinner-grow"></div>
    <div id="spin-2" class="item spinner-grow"></div>
    <div id="spin-3" class="item spinner-grow"></div>
    <div id="spin-4" class="item spinner-grow"></div>
    <div id="spin-5" class="item spinner-grow"></div>
  </div>
</template>

<script>
export default {
  name: "Loader",
};
</script>

<style scoped>
.item {
  margin-left: 1em;
  width: 1.5rem;
  height: 1.5rem;
}
#spin-1 {
  color: rgb(100, 160, 132);
}
#spin-2 {
  color: rgb(113, 169, 120);
}
#spin-3 {
  color: rgb(78, 144, 158);
}
#spin-4 {
  color: rgb(110, 201, 186);
}
#spin-5 {
  color: rgb(110, 230, 200);
}
</style>