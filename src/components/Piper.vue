<template>
  <div class="container">
    <div class="text">PiperNet Is Here</div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  width: 100%;
  height: 403px;
  background-image: url(./img/image.png);
}

.text {
  font-style: normal;
  font-weight: 500;
  font-size: 72px;
  line-height: 84px;
  text-align: center;
  color: #ffffff;
  padding-top: 160px;
}

@media (max-width: 815px) {
  .container {
    height: 270px;
  }
  .text {
    font-weight: 400;
    font-size: 43px;
    line-height: 48px;
    padding-top: 101px;
  }
}
</style>
