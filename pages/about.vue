<template>
  <div>
    <Navbar/>
    <main>
        <div class="left">
          <div class="about-card">
            <p>Passion</p>
            <h3>A journey of truth, with no destination.</h3>
            <p>Here at Outdoor Vibrations we believe that the road to growth should have no end. With many paths of improvement, inner growth and strength is achieved with every step.</p>
            <p>Join us on this journey as we venture to topics of passion, health, outdoor tips, and other topics related to this great love. Whether your connection to nature is vibrant, or are looking to taking your first steps. Adventure is better with company.</p>
          </div>
        </div>
        <div class="right">
        <img src="../assets/about-pic.png" alt="">
        </div>
    </main>
    <img class="vector" src="../assets/vector.png" alt="">
    <!-- <TheFooter/> -->
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

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Montserrat', sans-serif;
}

main {
    margin-top: 40px;
    height: 70vh;
    display: grid;
    grid-template-columns: 1fr 1fr;
    font-family: 'Montserrat', sans-serif;
}
.left {
  display: flex;
  justify-content: center;
  align-items: center;
}

.right {
    /* padding: 40px 0 40px 100px; */
    display: flex;
    justify-content: center;
    align-items: center;
}

.right img {
  height: 448px;
  /* width: 35rem; */
}

.about-card {
  /* font-family: 'Roboto', sans-serif; */
  /* margin-top: 3rem; */
  /* margin-left: 2.5rem; */
  padding: 0 18px;
  height: 500px;
  width: 500px;
  border-radius: 10px;
  text-align: center;
  background-color: #40916C;
  color: #fff;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
}

.about-card p {
  /* margin-top: 2rem; */
  font-size: 16px;
}

.about-card h3 {
  /* margin-top: 1.5rem; */
  font-size: 22px;
}

.vector {
  position: absolute;
  bottom: 0rem;
  left: 0;
  z-index: -1;
  width: 100vw;
  height: 50vh;
}
</style>