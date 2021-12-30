<template>
  <div>
    <Nav class="nav_bar" />
    <img class="promo" src="../static/service_promo.png">
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

<style>
.promo{
  height: 100%;
  width: 100%;
}
.nav_bar{
  background-image: url('static/hero2.jpg');
  background-size: cover;
  background-position-y: 19%;
  opacity: 90%;
}
</style>
