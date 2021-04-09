<template>
  <div>
    <div>
    <Navbar/>
    <div class="containers">
        <div class="left about-card">
          <p>Passion</p>
          <h3>A journey of truth, with no destination.</h3>
          <p>Here at Outdoor Vibrations we believe that the road to growth should have no end. With many paths of improvement, inner growth and strength is achieved with every step.</p>
          <p>Join us on this journey as we venture to topics of passion, health, outdoor tips, and other topics related to this great love. Whether your connection to nature is vibrant, or are looking to taking your first steps. Adventure is better with company.</p>
        </div>
        <div class="right">
        <img src="../assets/about-pic.png" alt="">
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
    name: 'about',
    components: {
        Navbar,
        TheFooter
    }
}
</script>

<style>
.about-card {
  /* font-family: 'Roboto', sans-serif; */
  margin-top: 3rem;
  margin-left: 2.5rem;
  padding: 0 18px;
  height: 500px;
  width: 80%;
  border-radius: 10px;
  text-align: center;
  background-color: #40916C;
  color: #fff;
}

.about-card p {
  margin-top: 2rem;
  font-size: 1.25vw;
}

.about-card h3 {
  margin-top: 1.5rem;
  font-size: 2vw;
}
</style>