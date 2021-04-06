<template>
<div>
  <Navbar/>
  <div class="container">
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
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Montserrat';
}
.vector {
  position: absolute;
  bottom: 0rem;
  left: 0;
  z-index: -1;
  width: 100vw;
  height: 50vh;
}

.container {
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
  /* grid-area: right; */
  margin-top: 3.5rem;
}

.container h1 {
  font-size: 64px;
  width: 500px;
  margin-left: 3.5rem;
  margin-top: 4rem;
  color: #40916C;
  font-weight: 700;
  background: -webkit-linear-gradient(#58B727, #40916C);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: none;
  /* margin-bottom: 2rem; */
}

.container h2 {
  font-size: 36px;
  width: 500px;
  margin-left: 3.5rem;
  padding-top: 2.5rem;
}

.container .button {
  margin-left: 3rem;
  margin-top: 1rem;
  background: linear-gradient(45deg, #58B727, #40916C);
  /* background-color: #40916C; */
  color: #fff;
  /* padding-top: 100px; */
  /* height: 90px;
  width: 300px;
  background-color: aquamarine; */
}
</style>