<template>
  <div class="hero_container">
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
    <nuxt-link to="/Services">
      <button class="btn" @click="log">
        <img src="../static/hookah.jpg">
      </button>
    </nuxt-link>
  </div>
</template>

<script>
export default {
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
.btn:hover{
  background: bisque;
}
.btn:active{
  background-color:goldenrod;
  box-shadow: 0 5px #666;
  transform: translateY(4px);
}
img {
  height: 500px;
  width: 700px;
}
.hero_container {
  height: 100%;
  width: 100%;
  color: bisque;
  display: flex;
  flex-direction: row;
}
.hours_div{
    color: bisque;
    font-size: x-large;
    padding: 0.5rem;
}
</style>
