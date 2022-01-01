<template>
  <div>
    <div class="containera">
      <Nav />
    </div>
    <div class="navigations">
      <h1 class="sm_titles">
        Follow Us On Social Media!
      </h1>
      <div class="sms">
        <img class="fbs" src="../static/icn-facebook.svg">
        <img class="igs" src="../static/icn-instagram.svg">
        <img class="tws" src="../static/icn-negative.svg">
      </div>
      <Body />
      <HookahBar />
      <Body2 />
      <Body3 />
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
