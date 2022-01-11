<template>
  <div class="special__container">
    <h1>Open 5pm-2am Tuesday-Sunday </h1>
    <Nav />
    <div class="service_sm">
      <a href="https://www.facebook.com/Al-Hayba-Hookah-Lounge-103226428922613" target="_blank"><img class="fbs_s" src="../static/icn-facebook.svg"></a>
      <a href="https://instagram.com" target="_blank"><img class="igs_s" src="../static/icn-instagram.svg"></a>
      <a href="https://twitter.com" target="_blank"><img class="tws_s" src="../static/icn-negative.svg"></a>
    </div>
    <div class="navigation_special" />
    <div class="hookah_brands">
      <img class="promo" src="../static/brand2.png">
    </div>
    <div class="banner">
      <img class="promo" src="../static/newflavors.png">
    </div>
    <div class="beverages_cold">
      <img class="promo" src="../static/newbeverage.png">
    </div>
    <div class="juice">
      <img class="promo" src="../static/newjuice2.png">
    </div>
    <div class="hot">
      <img class="promo" src="../static/newhotbev2.png">
    </div>
    <div class="food">
      <img class="promo" src="../static/food2.png">
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
