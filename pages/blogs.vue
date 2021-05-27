<template>
  <div>
      <Navbar />
      <div class="featured">
          <div class="featured-text">
              <p class="featured-category">Featured</p>
              <h2 class="featured-title">The outdoors, breaking down the walls and reconnecting.</h2>
              <p class="featured-date">May 12, 2021</p>
          </div>
          <div class="featured-image">

          </div>
      </div>
  </div>
</template>

<script>
import Navbar from '../components/Navbar'
export default {
    name: 'blogs',
    components: {
        Navbar
    }
}
</script>

<style scoped>
.featured {
    display: flex;
    justify-content: center;
    margin-top: 40px;
    font-family: 'Roboto', sans-serif;
}

.featured-text {
    height: 350px;
    width: 600px;
    background-color: #40916c;
    padding-left: 30px;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
}

.featured-category {
    font-size: 16px;
    font-weight: 500;
    color: #1b4332;
}

.featured-title {
    font-size: 48px;
    font-weight: 600;
    color: #fff;
}

.featured-date {
    font-size: 16px;
    font-weight: 400;
    color: #e6e6e6;
}

.featured-image {
    height: 350px;
    width: 600px;
    background-image: url('~@/assets/autumn.png');
}
</style>