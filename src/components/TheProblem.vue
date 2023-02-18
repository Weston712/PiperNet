<template>
  <div class="container">
    <div id="problem" class="header">The Problem</div>
    <div class="paragraph">
      Beneath the flashy homepages of your favorite sites lurk Hooli™ and other evil corporations out to hoard and sell
      your most personal data.<br />
      <br />
      What was built to be the ultimate platform for the free sharing of knowledge has turned into a money-hungry
      monster feasting on our privacy and freedom. <br />
      <br />
      But fear not, for Pied Piper has the answer! And it’s simple: An autonomous peer-to-peer network featuring
      distributed storage powered by universal compression, accelerated scheduling allocation, and end-to-end
      encryption.<br />
      <br />
      Put even simpler — it’s the internet, completely decentralized.
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  width: 100%;
  height: 719px;
  background: #eeeeee;
}

.header {
  font-style: normal;
  font-weight: 500;
  font-size: 64px;
  line-height: 75px;
  text-align: center;
  color: #007765;
  padding-top: 68px;
}

.paragraph {
  font-style: normal;
  font-weight: 400;
  font-size: 32px;
  line-height: 38px;
  color: #000000;
  margin: 16px 450px 92px 451px;
}

@media (max-width: 1701px) {
  .paragraph {
    font-size: 28px;
    line-height: 35px;
  }
}

@media (max-width: 1592px) {
  .paragraph {
    font-size: 26px;
    line-height: 26px;
    margin: 16px 315px 92px 316px;
  }

  .container {
    width: 100%;
    height: 580px;
  }
}

@media (max-width: 1186px) {
  .paragraph {
    font-size: 25px;
    line-height: 28px;
    margin: 16px 101px 92px 102px;
  }
}

@media (max-width: 815px) {
  .header {
    font-weight: 500;
    font-size: 43px;
    line-height: 58px;
  }
  .paragraph {
    font-size: 18px;
    line-height: 19px;
    margin: 16px 59px 29px 59px;
  }
}
</style>
