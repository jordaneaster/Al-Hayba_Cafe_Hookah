<template>
  <div class="container">
    <div class="nav_bar">
      <Nav />
    </div>
    <div class="navigation">
      <h1 class="sm-title">Follow Us On Social Media!</h1>
      <div class="sm">
        <img class="logo fb" src="../static/icn-facebook.svg">
        <img class="logo ig" src="../static/icn-instagram.svg">
        <img class="logo tw" src="../static/icn-negative.svg">
      </div>
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
<style scoped>
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
  background-color: white;
}
.body{
  grid-area: 4/1/span 1/span 4;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  background-image: url('static/hero3.jpg');
  background-size: cover;  width: 100%;
  padding: 6px;
}
.body2{
  grid-area: 3/1/span 1/span 4;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  background-color: black;
  padding: 6px
}
.body3{
  grid-area: 5/1/span 1/span 4;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  background-image: url('static/hero3.jpg');
  background-size: cover;
  width: 100%;
  padding: 6px;
}
.container{
  display: grid;
  grid-template-rows: 924px 1fr 1fr 1fr 1fr;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  width: 100%;
  height: 100%;
  margin: 0;
}
.fb{
  background-color: dodgerblue;
}
.ig{
  background-color: crimson;
}
.tw{
  background-color: dodgerblue;
}
.nav_bar{
  grid-area: 1/1/span 1/span 4;
  width: 100%;
  height: 100%;
  background-image: url('static/hookah_header.png');
  background-size: cover;
}
.navigation{
  grid-area: 2/1/span 1/span 4;
  background-color: black;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.sm-title{
  color: white;
  font-size: 44pt;
  text-align: center;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}
.sm{
  align-items: center;
  display: flex;
  flex-direction: row;
  justify-content: center;
}
.logo{
  height: 50%;
  width:50%;
}
footer{
  grid-area: 5/1/span 1/span 4;
  width: 100%
}

@media screen and (max-width: 960px) {
  .container{
    grid-template-rows: 290px 1fr 1fr 1fr 1fr;
  }
  .nav_bar{
  width: 400px;
  height: auto;
  background-image: url('static/hookah_header.png');
  background-size: contain;
  background-repeat: none;
  }
}
</style>
