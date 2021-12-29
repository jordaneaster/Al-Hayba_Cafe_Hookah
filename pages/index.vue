<template>
  <div class="container">
    <div class="nav_bar">
      <Nav />
    </div>
    <div class="body">
      <Body />
    </div>
    <div class="body2">
      <Body-2 />
    </div>
    <div class="body3">
      <Body3 />
    </div>
    <!-- <footer>
      <Footer />
    </footer> -->
  </div>
</template>

<script>
import Nav from '../components/Nav.vue'
// import Footer from '../components/Footer.vue'
import Body from '../components/Body.vue'
import Body2 from '../components/Body2.vue'
import Body3 from '../components/Body3.vue'
export default {
  components: {
    Nav,
    // Footer,
    Body,
    Body2,
    Body3
  }
}
</script>
<style>
footer{
  width: 100%;
  background-color:firebrick;
  opacity: 80%;
  border: 1px;
  border-radius: 12px;
  position: fixed;
  grid-area: 5/1/span 1/span 4;
}
html{
  background-image: url('static/hookah.jpg');
  background-size: contain;
}
.body{
  grid-area: 3/1/span 1/span 4;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
 background-image: url('static/hero3.jpg');
  background-size: cover;  width: 100%;
}
.body2{
  grid-area: 2/1/span 1/span 4;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  background-color: black;
}
.body3{
  grid-area: 4/1/span 1/span 4;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  background-image: url('static/hero3.jpg');
  background-size: cover;
  width: 100%;
}
.container{
  display: grid;
  grid-template-rows: 160px 1fr 1fr 1fr 1fr;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  width: 100%;
  height: 100%;
  margin: 0;
}
.nav_bar{
  grid-area: 1/1/span 1/span 4;
}
footer{
  grid-area: 5/1/span 1/span 4;
  width: 100%
}
</style>
