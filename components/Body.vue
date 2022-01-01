<template>
  <div class="hero_containersw">
    <h1 class="sm_titles">Our Services</h1>
    <div class="hero">
      <div class="containerSize">
    <nuxt-link to="/services">
        <img class="imgs" src="../static/Services.png">
    </nuxt-link>
      </div>
      <div class="containerSize">
    <nuxt-link to="/specials">
        <img class="imgs" src="../static/specials.png">
    </nuxt-link>
      </div>
    <div class="containerSize">
    <nuxt-link to="/reservations">
        <img class="imgs" src="../static/reservations.png">
    </nuxt-link>
    </div>
    </div>
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
