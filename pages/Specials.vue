<template>
  <div class="special__container">
    <div class="navigation">
      <Nav class="nav_bar" />
    </div>
    <div class="banner">
      <img class="promo" src="../static/specials_promo.png">
    </div>
  </div>
</template>

<script>
import Nav from '../components/Nav.vue'
export default {
  components: {
    Nav
  }
}
</script>

<style scoped>
.special__container{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-template-rows: 325px 1fr;
}
.navigation{
  position: fixed;
  display: grid;
  grid-area: 1/1/span 1/span 4;
  width: 100%;
}
.nav_bar{
  background-image: url('static/hero2.jpg');
  background-size: cover;
  background-position-y: 19%;
  opacity: 90%;
  height: 320px;
}
.promo{
width: 100%;
height: 100%;
border: 0.1rem;
border-style: solid;
border-color: white;
}
.banner{
display: grid;
grid-area: 2/1/span 1/span 4;
}
</style>
