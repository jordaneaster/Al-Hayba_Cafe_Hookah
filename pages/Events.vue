<template>
  <div class="event_container">
    <Nav />
    <div class="event_sm">
      <img class="fbs_e" src="../static/icn-facebook.svg">
      <img class="igs_e" src="../static/icn-instagram.svg">
      <img class="tws_e" src="../static/icn-negative.svg">
    </div>
    <div class="event_hero" />
    <h1 class="event_heading">
      Cater Your Next Event Here!
    </h1>
    <div class="event_para">
      <p class="para">
        Planning an event? Al Hayba Hookah Lounge has the perfect space available for you and your guests. Hosting and event can be a daunting task, we make it easier on the host with our plush rooms and amenities
      </p>
      <nuxt-link to="/reservations">
        <button class="event_schedule">
          <p class="button_event">
            Schedule Now!
          </p>
        </button>
      </nuxt-link>
      <ul class="event_list">
        <li class="event_list-item">
          2 Private Rooms
        </li>
        <li class="event_list-item">
          Hookah Specials
        </li>
        <li class="event_list-item">
          Drink Specials
        </li>
        <li class="event_list-item">
          6 flat screens
        </li>
        <li class="event_list-item">
          Music
        </li>
      </ul>
    </div>
    <div class="event_content">
      <img class="event_img" src="../static/reservation4.jpg">
      <img class="event_img" src="../static/reservation3.jpg">
    </div>
    <div class="event_sm">
      <img class="fbs_e" src="../static/icn-facebook.svg">
      <img class="igs_e" src="../static/icn-instagram.svg">
      <img class="tws_e" src="../static/icn-negative.svg">
    </div>
  </div>
</template>

<script>
import '../styles/events.css'
import Nav from '../components/Nav.vue'
export default {
  components: {
    Nav
  }
}
</script>

<style>

</style>
