<template>
  <div class="un">
    <Nav />
    <div class="event_hero" />
    <div class="rule_promo">
      <img class="imgw" src="../static/rules_promo.png">
    </div>
    <div class="foot-rules">
      <a href="https://facebook.com" target="_blank"><img class="fbs-rules" src="../static/icn-facebook.svg"></a>
      <a href="https://instagram.com" target="_blank"><img class="fbs-rules" src="../static/icn-instagram.svg"></a>
      <a href="https://twitter.com" target="_blank"><img class="fbs-rules" src="../static/icn-negative.svg"></a>
      <p class="al">&copy; Al Hayba Hookah Lounge</p>
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
