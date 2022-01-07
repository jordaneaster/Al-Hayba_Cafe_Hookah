<template>
  <div class="special__container">
    <h1>Open 5pm-2am Tuesday-Sunday </h1>
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
    <div class="foot-rules">
      <a href="https://facebook.com" target="_blank"><img class="fbs-rules" src="../static/icn-facebook.svg"></a>
      <a href="https://instagram.com" target="_blank"><img class="fbs-rules" src="../static/icn-instagram.svg"></a>
      <a href="https://twitter.com" target="_blank"><img class="fbs-rules" src="../static/icn-negative.svg"></a>
      <p class="al">
        &copy; Al Hayba Hookah Lounge
      </p>
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
