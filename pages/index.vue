<template>
<div>
  <div>
  <Navbar/>
  <div class="containers">
    <div class="left">
      <h1 class="title">Connecting to Nature</h1>
      <h2 class="subtitle">Have a love for all things that are outdoors?</h2>
      <b-button size="is-large">Join Now</b-button>
      <b-button size="is-large">Read Blog</b-button>
    </div>
    <div class="right">
      <img src="../assets/landing-pic.png" alt="">
    </div>
  </div>
  <img class="vector" src="../assets/vector.png" alt="">
</div>
<TheFooter/>
</div>

</template>

<script>
import Navbar from '../components/Navbar'
import TheFooter from '../components/TheFooter'

export default {
  components: {
    Navbar,
    TheFooter
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Montserrat', sans-serif;
}
.vector {
  position: absolute;
  bottom: 0rem;
  left: 0;
  z-index: -1;
  width: 100vw;
  height: 50vh;
}

.containers {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-areas: "left right";
}

.right {
  grid-area: right;
  display: flex;
  justify-content: center;
  align-items: center;
}

.left {
  grid-area: left;
}

img {
  margin-top: 3.5rem;
}

.containers h1 {
  font-size: 64px;
  width: 31rem;
  margin-left: 3.5rem;
  margin-top: 4rem;
  color: #40916C;
  font-weight: 700;
  background: -webkit-linear-gradient(#40916C, #58B727);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: none;
}

.containers h2 {
  font-size: 36px;
  width: 31rem;
  margin-left: 3.5rem;
  padding-top: 2.5rem;
}

.containers .button {
  margin-left: 3.5rem;
  margin-top: 1rem;
  background: linear-gradient(180deg, #58B727, #40916C);
  color: #fff;
}

.footer-container {
  margin-top: 7rem;
}
</style>