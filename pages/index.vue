<template>
  <div>
    <div class="containera">
      <h1>Open 5pm-2am Tuesday-Sunday </h1>
      <Nav />
      <div class="service_sm">
        <a href="https://www.facebook.com/Al-Hayba-Hookah-Lounge-103226428922613" target="_blank"><img class="fbs_s" src="../static/icn-facebook.svg"></a>
        <a href="https://instagram.com" target="_blank"><img class="igs_s" src="../static/icn-instagram.svg"></a>
        <a href="https://twitter.com" target="_blank"><img class="tws_s" src="../static/icn-negative.svg"></a>
      </div>
    </div>
    <div class="navigations">
      <h1 class="sm_titles">
        Follow Us On Social Media!
      </h1>
      <div class="sms">
        <a href="https://facebook.com" target="_blank"><img class="fbs" src="../static/icn-facebook.svg"></a>
        <a href="https://instagram.com" target="_blank"><img class="igs" src="../static/icn-instagram.svg"></a>
        <a href="https://twitter.com" target="_blank"><img class="tws" src="../static/icn-negative.svg"></a>
      </div>
      <Body />
      <HookahBar />
      <Body2 />
      <Body3 />
      <div class="foot-rules">
        <a href="https://facebook.com" target="_blank"><img class="fbs-rules" src="../static/icn-facebook.svg"></a>
        <a href="https://instagram.com" target="_blank"><img class="fbs-rules" src="../static/icn-instagram.svg"></a>
        <a href="https://twitter.com" target="_blank"><img class="fbs-rules" src="../static/icn-negative.svg"></a>
        <p class="al">
          &copy; Al Hayba Hookah Lounge
        </p>
      </div>
    </div>
  </div>
</template>
<script>
import Nav from '../components/Nav.vue'
import '../styles/index.css'
import Body from '../components/Body.vue'
import Body2 from '../components/Body2.vue'
import Body3 from '../components/Body3.vue'
import HookahBar from '../components/hookahBar.vue'
export default {
  components: {
    Nav,
    Body,
    HookahBar,
    Body2,
    Body3

  }
}
</script>
