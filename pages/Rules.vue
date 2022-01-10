<template>
  <div class="un">
    <h1>Open 5pm-2am Tuesday-Sunday </h1>
    <Nav />
    <div class="service_sm">
      <a href="https://www.facebook.com/Al-Hayba-Hookah-Lounge-103226428922613" target="_blank"><img class="fbs_s" src="../static/icn-facebook.svg"></a>
      <a href="https://instagram.com" target="_blank"><img class="igs_s" src="../static/icn-instagram.svg"></a>
      <a href="https://twitter.com" target="_blank"><img class="tws_s" src="../static/icn-negative.svg"></a>
    </div>
    <div class="event_hero" />
    <div class="rule_promo">
      <img class="imgw" src="../static/rules2.png">
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
import '../styles/rules.css'
import Nav from '../components/Nav.vue'
export default {
  components: {
    Nav
  }
}
</script>

<style>

</style>
