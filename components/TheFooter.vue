<template>
  <div class="footer-container">
      <div class="top-row">
          <div class="top-left">
                <h2>Outdoor Vibration</h2>
                <NuxtLink to="/">Home</NuxtLink>
                <NuxtLink to="/about">About</NuxtLink>
                <NuxtLink to="/">Blog</NuxtLink>
          </div>
          <div class="top-right">
            <p>Connect with us</p>
            <form>
              <input class="email" type="email" name="email" placeholder="Your email here">
              <!-- <input type="submit" name="Subscribe" placeholder="Subscribe"> -->
              <input class="sub-btn" type="button" value="Subscribe">
            </form>
          </div>
      </div>
      <div class="bottom-row">
          <p>Follow Us</p>
          <a href="/">
            <img src="../assets/instagram.png" alt="">
          </a>
          <a href="/">
            <img src="../assets/facebook.png" alt="">
          </a>
          <a href="/">
            <img src="../assets/youtube.png" alt="">
          </a>
          <a href="/">
            <img src="../assets/twitter.png" alt="">
          </a>
      </div>
  </div>
</template>

<script>
export default {
    name: 'TheFooter'
}
</script>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.footer-container {
    /* display: grid; */
    /* grid-template-rows: 200px 150px; */
    /* grid-template-areas: "top bottom"; */
    z-index: -1;
    height: 350px;
    /* width: 100vw; */
}

.top-row {
    /* grid-area: top; */
    background-color: #40916C;
    height: 200px;
}

.top-left {
    display: inline-block;
    margin-top: 40px;
    margin-left: 3.5rem;
}

.top-left h2 {
    font-size: 32px;
    color: #fff;
    margin-bottom: 1.5rem;
}

.top-left .nuxt-link-active {
    margin-right: 1rem;
    color: #fff;
    font-size: 16px;
}

.top-right {
    display: inline-block;
    position: absolute;
    right: 3.5rem;
    margin-top: 44px;
}

.top-right p {
    font-size: 24px;
    color: #fff;
    margin-bottom: 1.5rem;
}

.top-right input {
    height: 40px;
    background-color: #40916C;
    color: #fff;
    border-color: #fff;
}

.email {
    width: 345px;
}

.sub-btn {
    /* font-size: 14px; */
    width: 110px;
}

::placeholder { /* Chrome, Firefox, Opera, Safari 10.1+ */
  color: #fff;
  opacity: 1; /* Firefox */
  padding-left: 8px;
}

.bottom-row {
    /* grid-area: bottom; */
    background-color: #1B4332;
    height: 150px;
    color: #fff;
    font-size: 20px;
    /* display: flex; */
    /* justify-content: center; */
    /* align-items: center; */
    text-align: center;
}

.bottom-row p {
    padding-top: 1rem;
    margin-bottom: -2rem;
}

.bottom-row img {
    height: 40px;
    width: 40px;
    /* padding: 0 4px; */
}
</style>