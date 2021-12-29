<template>
  <div class="hero_container">
    <nuxt-link to="/events">
      <button class="btn" @click="log">
        <img src="../static/events.png">
      </button>
    </nuxt-link>
    <nuxt-link to="/shop">
      <button class="btn" @click="log">
        <img src="../static/smoke.png">
      </button>
    </nuxt-link>
    <nuxt-link to="/rules">
      <button class="btn" @click="log">
        <img src="../static/rules.png">
      </button>
    </nuxt-link>
  </div>
</template>

<script>
export default {
  methods: {
    log () {
      console.log('firing!')
    }
  }
}
</script>

<style>
.row_b{
  display: grid;
  grid-row-start: 2;
  grid-row-end: 3;
  grid-column-start: 1;
  grid-column-end: 3;
}
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
  width: 500px;
  border-radius: 10px;
}
.hero_container {
  height: 100%;
  width: 100%;
  color: bisque;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.hours {
  height: 100%;
  width: 100%;
  grid-area: 1/1 / span 1 / span 1;
  justify-items: stretch;
}
.reservation {
  height: 100%;
  width: 100%;
  grid-area: 1/2 / span 1 / span 1;

  justify-content: center;
}
.content {
  height: 100%;
  width: 100%;
  grid-area: 1/3 / span 1 / span 1;
  justify-content: center;
}
p {
  font-size: 22pt;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
</style>
