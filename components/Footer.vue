<template>
  <div class="footer-container">
    <div class="footerBox">
      <div class="footer-left-item">
        <n-link class="footerRoute" to="/">
          Home
        </n-link>
        <n-link class="footerRoute" to="/reservations">
          Reservations
        </n-link>
        <n-link class="footerRoute" to="/about">
          About
        </n-link>
        <n-link class="footerRoute" to="/contact">
          Contact
        </n-link>
      </div>
      <div class="footer-align">
        <img class="socialmedia" src="../static/icn-facebook.svg" alt="facebook">
        <img class="socialmedia" src="../static/icn-instagram.svg" alt="instagram">
        <img class="socialmedia" src="../static/icn-negative.svg" alt="twitter">
      </div>
    </div>
    <div class="location">
      <img class="socialmedia" src="../static/location.svg" alt="point">
      <p> Al Hayba Hookah Lounge </p>
      <p> 6454 Pearl Road </p>
      <p> Parma Heights, Ohio </p>
      <p> 44130 </p>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.location{
  display: flex;
  flex-direction: column;
  padding: 6px;
  grid-area: 1/2/span 1/span 1;
  border-right: 1px solid bisque;
  align-items: center;
  color: bisque;
}
.footerBox{
   border-right: 1px solid bisque;
}
.footer-container{
  display: grid;
  grid-template-rows: 400px;
  grid-template-columns: 1fr 1fr 1fr;
}
.footer-align{
   display: flex;
   align-items: center;
}
.socialmedia{
    padding-right: 20px;
    padding-left: 20px;
    width: 60px;
    cursor: pointer;
}
.footerRoute{
    font-family: 'Russo One', sans-serif;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 100%;
    letter-spacing: 0.02em;
    color: bisque;
    cursor: pointer;
    margin: 0;
    padding: 10px 20px 10px;
}
.footer-left-item{
    display: flex;
    flex-direction: column;
    padding: 10px;
}
</style>
