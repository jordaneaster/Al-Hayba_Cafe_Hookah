<template>
  <div class="container">
    <div class="nav_bar">
      <Nav />
    </div>
    <div class="body">
      <Body />
    </div>
    <Footer />
  </div>
</template>

<script>
import Nav from '../components/Nav.vue'
import Footer from '../components/Footer.vue'
import Body from '../components/Body.vue'
export default {
  components: {
    Nav,
    Footer,
    Body
  }
}
</script>
<style>
html{
  background-image: url('static/hookah.jpg');
  background-size: cover;
}
.body{
  grid-area: 2/1/span 3/span 4;
}
.container{
  display: grid;
  grid-template-rows: 1fr 1fr 1fr 1fr 1fr;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  row-gap: 10px;
  width: 100%;
}
.nav_bar{
  grid-area: 1/1/span 1/span 4;
}
footer{
  grid-area: 5/1/span 2/span 4;
  width: 100%
}
</style>
