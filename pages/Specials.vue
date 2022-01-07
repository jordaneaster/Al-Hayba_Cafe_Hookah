<template>
  <div class="special__container">
    <div class="navigation_special">
      <Nav class="nav_bar" />
    </div>
    <div class="banners">
      <img class="promos" src="../static/brand-special.png">
    </div>
    <div class="foot">
      <a href="https://facebook.com" target="_blank"><img class="fbs-special" src="../static/icn-facebook.svg"></a>
      <a href="https://instagram.com" target="_blank"><img class="fbs-special" src="../static/icn-instagram.svg"></a>
      <a href="https://twitter.com" target="_blank"><img class="fbs-special" src="../static/icn-negative.svg"></a>
      <p>&copy; Al Hayba Hookah Lounge</p>
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
