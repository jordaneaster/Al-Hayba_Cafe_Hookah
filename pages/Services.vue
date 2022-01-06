<template>
  <div class="special__container">
    <Nav />
    <div class="service_sm">
      <img class="fbs_s" src="../static/icn-facebook.svg">
      <img class="igs_s" src="../static/icn-instagram.svg">
      <img class="tws_s" src="../static/icn-negative.svg">
    </div>
    <div class="navigation_special" />
    <div class="banner">
      <img class="promo" src="../static/newpromo.png">
    </div>
  </div>
</template>

<script>
import '../styles/services.css'
import Nav from '../components/Nav.vue'
export default {
  components: {
    Nav
  }

}
</script>
