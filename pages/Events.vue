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
      <div class="abc">
        <p class="paras">
          Planning an event? Al Hayba Hookah Lounge has the perfect space
          available for you and your guests. Hosting and event can be a daunting
          task, we make it easier on the host with our plush rooms and amenities
        </p>
      </div>
      <div class="abc">
        <ul class="event_lists">
          <li class="event_list_items">
            2 Private Rooms
          </li>
          <li class="event_list_items">
            Hookah Specials
          </li>
          <li class="event_list_items">
            Drink Specials
          </li>
          <li class="event_list_items">
            6 flat screens
          </li>
          <li class="event_list_items">
            Music
          </li>
        </ul>
      </div>
    </div>
    <div class="abcc">
      <nuxt-link to="/reservations">
        <button class="event_schedules">
          Schedule Now!
        </button>
      </nuxt-link>
    </div>
    <div class="event_content">
      <div>
        <img class="event_img" src="../static/reservation4.jpg">
      </div>
      <div>
        <img class="event_img" src="../static/reservation3.jpg">
      </div>
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
