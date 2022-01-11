<template>
  <div class="event_container">
    <h1>Open 5pm-2am Tuesday-Sunday </h1>
    <Nav />
    <div class="service_sm">
      <a href="https://www.facebook.com/Al-Hayba-Hookah-Lounge-103226428922613" target="_blank"><img class="fbs_s" src="../static/icn-facebook.svg"></a>
      <a href="https://instagram.com" target="_blank"><img class="igs_s" src="../static/icn-instagram.svg"></a>
      <a href="https://twitter.com" target="_blank"><img class="tws_s" src="../static/icn-negative.svg"></a>
    </div>
    <div class="event_hero" />
    <h1 class="event_heading">
      Cater Your Next Event Here!
    </h1>
    <div class="event_para">
      <div class="abc">
        <p class="paras">
          Planning an event? Al Hayba Hookah Lounge has the perfect space
          available for you and your guests. Wedddings, engagement parties, work gatherings, funeral receptions, graduation parties. We can host up to 200 guests!
        </p>
        <p class="paras">
          Call <a class="telly" href="tel:4403052618">
            440-305-2618
          </a> today or click below to fill out the form and schedule now!
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
            8 flat screens
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
