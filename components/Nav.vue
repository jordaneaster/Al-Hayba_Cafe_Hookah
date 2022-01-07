<template>
  <div class="nav_container">
    <nav class="head_banner">
      <BurgerMenu class="burger" />
    </nav>
    <SideMenu class="side_menu">
      <ul class="sidebar-panel-nav">
        <nuxt-link to="/">
          <li class="link2">
            Home
          </li>
        </nuxt-link>
        <nuxt-link to="/services">
          <li class="link2">
            Services
          </li>
        </nuxt-link>
        <nuxt-link to="/reservations">
          <li class="link2">
            Book Now!
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
        <nuxt-link to="/rules">
          <li class="link2">
            Rules
          </li>
        </nuxt-link>
      </ul>
      <div class="hours_div">
        <h4 class="hours_open">
          (440)-555-5555
        </h4>
        <h4 class="hours_open">
          CLOSED
        </h4>
        <tr class="day_week">
          Monday
        </tr>
        <h4 class="hours_open">
          Open 5PM-2AM
        </h4>
        <div v-for="day in openDays" :key="day.id" class="days">
          <tr class="day_week">
            {{
              day
            }}
          </tr>
        </div>
      </div>
    </SideMenu>
  </div>
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

<style>
.burger {
  position: fixed;
}
.day_week {
  font-size: larger;
  color: black;
  font-style: normal;
}
.hours_div {
  color: bisque;
  font-size: x-large;
  padding: 4px;
  display: flex;
  flex-direction: column;
  padding: 4px;
  text-align: left;
}
.hours_open {
  color: black;
  font-style: normal !important;
  margin:0;
  padding-top: 10px;
  padding-bottom: 10px;
}
.pages {
  width: 200px;
  height: 200px;
  position: relative;
}
.link {
  color: none;
  font-style: normal;
}
.link2:hover {
  background-color: coral;
  padding: 4px;
  font-style: normal;
}
nav ul {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-content: center;
  margin: auto;
  padding: 8px;
  border: 0.5rem;
  border-style: solid;
  border-radius: 8px;
  list-style: none;
  width: 100%;
  height: 100%;
  font-style: normal;
}
li {
  color: black;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-size: xx-large;
  font-stretch: semi-expanded;
  font-weight: 800;
  letter-spacing: 0.3rem;
  text-shadow: 2rem;
  box-shadow: grey;
  list-style: none;
  font-style: normal;
  text-align: left;
}
h1 {
  font-family: "Parisienne", cursive;
  color: bisque;
  font-size: xx-large;
  text-shadow: 30%;
  font-style: normal;
}
.sidebar-panel-nav {
  display: flex;
  flex-direction: column;
  justify-content: left;
  background-color: antiquewhite;
  font-style: normal;
}
</style>
