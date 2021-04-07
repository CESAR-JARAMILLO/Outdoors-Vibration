<template>
  <div class="footer-container">
      <div class="top-row">

      </div>
      <div class="bottom-row">

      </div>
  </div>
</template>

<script>
export default {
    name: 'TheFooter'
}
</script>

<style>
.footer-container {
    display: grid;
    grid-template-rows: 2fr 1fr;
    grid-template-areas: "top bottom"
}

.top-row {
    grid-area: top;
    background-color: #40916C;
    height: 480px;
}

.bottom-row {
    grid-area: bottom;
    background-color: #1B4332;
    height: 200px;
}
</style>