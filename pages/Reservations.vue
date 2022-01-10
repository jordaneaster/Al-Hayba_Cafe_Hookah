<template>
  <div class="kaj">
    <h1>Open 5pm-2am Tuesday-Sunday </h1>
    <Nav />
    <div class="service_sm">
      <a href="https://www.facebook.com/Al-Hayba-Hookah-Lounge-103226428922613" target="_blank"><img class="fbs_s" src="../static/icn-facebook.svg"></a>
      <a href="https://instagram.com" target="_blank"><img class="igs_s" src="../static/icn-instagram.svg"></a>
      <a href="https://twitter.com" target="_blank"><img class="tws_s" src="../static/icn-negative.svg"></a>
    </div>
    <div class="container_form">
      <div class="box_form">
        <h1 class="reser">
          Book Now!
        </h1>
        <div class="boxing">
          <form
            name="contactus"
            action="/thanks"
            method="post"
            netlify
            netlify-honeypot="bot-field"
          >
            <input type="hidden" name="form-name" value="contactus">
            <div>
              <h1 class="name">
                Name
              </h1>
              <input class="input" placeholder="Name" type="text" name="name" required>
            </div>
            <div>
              <h1 class="name">
                Email
              </h1>
              <input class="input" type="email" placeholder="Email" name="email" required>
            </div>
            <div>
              <h1 class="name">
                Address
              </h1>
              <input class="input" type="text" placeholder="Address" name="address" required>
            </div>
            <div>
              <h1 class="name">
                Phone
              </h1>
              <input class="input" type="number" placeholder="Phone" name="phone" required>
            </div>
            <div>
              <h1 class="name">
                Event Date
              </h1>
              <input class="input" type="date" name="event_date">
            </div>
            <div>
              <h1 class="name">
                Party Size
              </h1>
              <input class="input" type="number" placeholder="Party Size" name="partysize" required>
            </div>
            <div>
              <h1 class="name">
                Amenities
              </h1>
              <input class="input" type="text" placeholder="Amenities" name="amenities" required>
            </div>
            <button class="submit" type="submit" value="Send message">
              Send
            </button>
          </form>
        </div>
      </div>
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
import '../styles/reservation.css'
export default {
  components: {
    Nav
  }
}
</script>

<style>
</style>
