<template>
  <div class="special__container">
    <div class="navigation_special">
      <h1>Open 5pm-2am Tuesday-Sunday </h1>
      <Nav class="nav_bar" />
      <div class="service_sm">
        <a href="https://www.facebook.com/Al-Hayba-Hookah-Lounge-103226428922613" target="_blank"><img class="fbs_s" src="../static/icn-facebook.svg"></a>
        <a href="https://instagram.com" target="_blank"><img class="igs_s" src="../static/icn-instagram.svg"></a>
        <a href="https://twitter.com" target="_blank"><img class="tws_s" src="../static/icn-negative.svg"></a>
      </div>
    </div>
    <div class="banners">
      <img class="promos" src="../static/brand-special.png">
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
import Nav from '../components/Nav.vue'
import '../styles/special.css'
export default {
  components: {
    Nav
  }
}
</script>
