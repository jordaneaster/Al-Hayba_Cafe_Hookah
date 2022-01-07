<template>
  <div class="special__container">
    <div class="navigation_special">
      <Nav class="nav_bar" />
    </div>
    <div class="banners">
      <img class="promos" src="../static/specials_promo.png">
    </div>
  </div>
</template>

<script>
import Nav from '../components/Nav.vue'
import '../styles/special.css'
export default {
  components: {
    Nav
  }
}
</script>
