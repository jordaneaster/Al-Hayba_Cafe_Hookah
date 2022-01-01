<template>
  <div class="hero_containersw">
    <div class="hero">
      <div class="containerSize">
        <nuxt-link to="/events">
          <img class="imgs" src="../static/events.png">
        </nuxt-link>
      </div>
      <div class="containerSize">
        <nuxt-link to="/shop">
          <img class="imgs" src="../static/smoke.png">
        </nuxt-link>
      </div>
      <div class="containerSize">
        <nuxt-link to="/rules">
          <img class="imgs" src="../static/rules.png">
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
