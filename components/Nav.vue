<template>
  <nav>
    <h1 class="title">
      Al Hayba Hookah Lounge
    </h1>
    <ul>
      <li>Home</li>
      <li>Reservations</li>
      <li>About</li>
      <li>Contact</li>
    </ul>
  </nav>
</template>

<script>
export default {}
</script>

<style scoped>
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
  color: bisque;
  font-family:'Russo One', sans-serif;
  font-size: x-large;
  font-style: oblique;
  letter-spacing: 0.3rem;
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
