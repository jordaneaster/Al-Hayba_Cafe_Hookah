<template>
  <div class="hero_containersw">
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
