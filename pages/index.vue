<template>
<div>
  <Navbar/>
  <h1 class="title">Connecting to Nature</h1>
  <h2 class="subtitle">Have a love for all things that are outdoors?</h2>
  <a href="">Join Now</a>
  <a href="">Read Blog</a>
  <img src="../assets/landing-pic.png" alt="">
  <img class="vector" src="../assets/vector.png" alt="">
</div>
</template>

<script>
import Navbar from '../components/Navbar'
export default {
  components: {
    Navbar
  }
}
</script>

<style>
.vector {
  position: absolute;
  bottom: -5rem;
  left: 0;
  z-index: -1;
}

h1 {
  margin-left: 3.5rem;
}

h2 {
  margin-left: 3.5rem;
}

a {
  margin-left: 3.5rem;
}
</style>