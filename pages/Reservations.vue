<template>
  <div>
    <Nav />
    <div class="container_form">
      <div class="box_form">
        <h1 class="reser">Booking Now</h1>
        <div class="boxing">
          <form
            name="contactus"
            action="/thanks"
            method="post"
            netlify
            netlify-honeypot="bot-field"
          >
            <input type="hidden" name="form-name" value="contactus" />
            <div>
              <h1 class="name">Name</h1>
              <input class="input" placeholder="Name" type="text" name="name" required />
            </div>
            <div>
              <h1 class="name">Email</h1>
              <input class="input" type="email" placeholder="Email" name="email" required />
            </div>
            <div>
              <h1 class="name">Address</h1>
               <input class="input" type="text" placeholder="Address" name="address" required />
            </div>
            <div>
              <h1 class="name">Phone</h1>
              <input class="input" type="number" placeholder="Phone" name="phone" required />
            </div>
            <div>
              <h1 class="name">Event Date</h1>
              <input class="input" type="date" name="event_date">
              </div>
            <div>
              <h1 class="name">Party Size</h1>
               <input class="input" type="number" placeholder="Party Size" name="partysize" required />
            </div>
            <div>
              <h1 class="name">Amenities</h1>
               <input class="input" type="text" placeholder="Amenities" name="amenities" required />
            </div>
            <button class="submit" type="submit" value="Send message">
              Send
            </button>
          </form>
        </div>
      </div>
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
