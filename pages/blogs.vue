<template>
    <div>
        <Navbar />
        <main>
            <div class="featured-blog">
                <div class="featured-text">
                    <p class="category">Featured</p>
                    <h2>The outdoors, breaking down the walls and reconnecting.</h2>
                    <p class="date">May 22, 2021</p>
                </div>
                <div class="featured-img">
                    <img src="../assets/autumn.png" alt="">
                </div>
            </div>
        </main>
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
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

main {
    margin-top: 40px;
    height: 70vh;
    /* display: grid;
    grid-template-columns: 1fr 1fr; */
    font-family: 'Roboto', sans-serif;
    display: flex;
    justify-content: center;
}

.featured-blog {
    width: 85vw;
    height: 280px;
    display: grid;
    grid-template-columns: 1fr 1fr;
}

.featured-text {
    background-color: #40916c;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    padding-left: 20px;
}

.featured-text .category {
    font-size: 18px;
    font-weight: 500;
    color: #1b4332;
}

.featured-text h2 {
    width: 85%;
    font-size: 40px;
    font-weight: 600;
    color: #fff;
}

.featured-text .date {
    font-size: 16px;
    font-weight: 300;
    color: #e6e6e6;
}

featured-img img {
    height: 380px;
    width: 100%;
}
</style>