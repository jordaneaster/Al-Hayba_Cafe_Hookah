<template>
  <div class="special__container">
    <div class="navigation_special">
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
