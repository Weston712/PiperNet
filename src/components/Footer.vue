<template>
  <div class="container">
    <div class="wraper">
      <p class="text">
        All other trademarks and copyrights are the property of their respective owners. Use of these names, trademarks
        and brands does not imply endorsement.
      </p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  width: 100%;
  height: 176px;
  background: #333333;
  padding-top: 50px;
}

.wraper {
  width: 25%;
  margin-left: auto;
  margin-right: auto;
}

.text {
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
  text-align: center;
  color: #ffffff;
}

@media (max-width: 937px) {
  .wraper {
    width: 40%;
  }
}

@media (max-width: 546px) {
  .container {
    height: 100px;
  }
  .wraper {
    width: 50%;
  }

  .text {
    font-size: 12px;
    line-height: 17px;
  }
}
</style>
