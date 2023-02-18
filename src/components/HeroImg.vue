<template>
  <div class="container">
    <div class="wraper">
      <h4 class="text">
        We’re in this together! All of our computers and phones join in a network to make the strongest supercomputer
        the world has ever seen.
      </h4>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  width: 100%;
  height: 423px;
  background-image: url(./img/Hero.png);
}

.wraper {
  width: 50%;
  height: 228px;
  margin-left: auto;
  margin-right: auto;
  padding-top: 80px;
}

.text {
  font-style: italic;
  font-weight: 500;
  font-size: 48px;
  line-height: 56px;
  text-align: center;
  color: #ffffff;
}
@media (max-width: 945px) {
  .wraper {
    padding-top: 75px;
  }
  .text {
    font-size: 39px;
    line-height: 45px;
  }
}

@media (max-width: 815px) {
  .wraper {
    padding-top: 75px;
  }

  .text {
    font-weight: 400;
    font-size: 35px;
    line-height: 42px;
  }
}

@media (max-width: 540px) {
  .container {
    height: 383px;
  }

  .wraper {
    width: 70%;
    padding-top: 58px;
  }
  .text {
    font-size: 28px;
    line-height: 36px;
  }
}
</style>
