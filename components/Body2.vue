<template>
  <div class="hero_container">
    <img src="../static/hookah.jpg">
  </div>
</template>

<script>
export default {}
</script>

<style scoped>

.btn:hover{
  background: bisque;
}
.btn:active{
  background-color:goldenrod;
  box-shadow: 0 5px #666;
  transform: translateY(4px);
}
img {
  height: 500px;
  width: 1000px;
}
.hero_container {
  height: 100%;
  width: 100%;
  color: bisque;
  display: flex;
  flex-direction: row;
}
</style>
