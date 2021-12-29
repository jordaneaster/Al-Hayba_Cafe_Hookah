<template>
  <nav>
    <h1 class="title">
      Al Hayba Hookah Lounge
    </h1>
    <ul>
      <nuxt-link class="link" to="/">
        <li>Home</li>
      </nuxt-link>
      <nuxt-link class="link" to="/Hours">
        <li>About</li>
      </nuxt-link>
      <nuxt-link class="link" to="/Contact">
        <li>Contact</li>
      </nuxt-link>
      <BurgerMenu />
    </ul>
    <SideMenu>
      <Sidebar>
        <ul class="sidebar-panel-nav">
          <nuxt-link to="/">
            <li class="link2">
              Home
            </li>
          </nuxt-link>
          <nuxt-link to="/services">
            <li class="link2">
              Hookah Services
            </li>
          </nuxt-link>
          <nuxt-link to="/reservations">
            <li class="link2">
              Reservations
            </li>
          </nuxt-link>
          <nuxt-link to="/events">
            <li class="link2">
              Events
            </li>
          </nuxt-link>
          <nuxt-link to="/specials">
            <li class="link2">
              Specials
            </li>
          </nuxt-link>
          <nuxt-link to="/shop">
            <li class="link2">
              Smoke Shop
            </li>
          </nuxt-link>
          <nuxt-link to="/rules">
            <li class="link2">
              Rules
            </li>
          </nuxt-link>
        </ul>
        <div class="hours_div">
          <h1>
            (440)-555-5555
          </h1>
          <h1 class="hours_open">
            CLOSED
          </h1>
          <tr class="day_week">
            Monday
          </tr>
          <h1 class="hours_open">
            Open 5PM-2AM
          </h1>
          <div v-for="day in openDays" :key="day.id" class="days">
            <tr class="day_week">
              {{ day }}
            </tr>
          </div>
        </div>
      </Sidebar>
    </SideMenu>
  </nav>
</template>

<script>
import SideMenu from '../components/SideMenu.vue'
import BurgerMenu from '../components/BurgerMenu.vue'
export default {
  components: {
    BurgerMenu,
    SideMenu
  },
  data () {
    return {
      openDays: {
        t: 'Tuesday',
        w: 'Wednesday',
        th: 'Thursday',
        f: 'Friday',
        s: 'Saturday',
        sn: 'Sunday'
      },
      closedDays: {
        m: 'Monday'
      }
    }
  }
}
</script>

<style scoped>
.day_week{
font-size: larger;
color: black;
}
.hours_div{
    color: bisque;
    font-size: x-large;
    padding: 0.5rem;
    display: flex;
    flex-direction: column;
    padding: 1rem;
}
.hours_open{
color: black;
}
.pages{
  width: 200px;
  height: 200px;
  position: relative;
}
.link{
  color: bisque;
}
.link2{
  color: black;
}
nav ul {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  margin: auto;
  padding: 8px;
  border: 0.5rem;
  border-style: solid;
  border-radius: 8px;
  list-style: none;
    }
li {
  color: white;
  font-family:'Impact''Russo One', sans-serif;
  font-size: x-large;
  font-style: oblique;
  letter-spacing: 0.3rem;
  text-shadow: 2rem;
  box-shadow: grey;
}
h1 {
  font-family: "Parisienne", cursive;
  color: bisque;
  font-size: xx-large;
  text-shadow: 30%;
}
.title {
  font-size: xx-large;
  color: #fff;
  text-align: center;
  animation: glow 1s ease-in-out infinite alternate;
}
.sidebar-panel-nav{
  display: flex;
  flex-direction: column;
  justify-content: left;
}

@-webkit-keyframes glow {
  from {
    text-shadow: 0 0 10px grey, 0 0 20px grey, 0 0 30px bisque, 0 0 40px bisque,
      0 0 50px bisque, 0 0 60px bisque, 0 0 60px bisque;
  }
  to {
    text-shadow: 0 0 20px grey, 0 0 30px bisque, 0 0 40px bisque,
      0 0 50px bisque, 0 0 60px bisque, 0 0 70px bisque, 0 0 80px bisque;
  }
}
</style>
