<template>
  <div class="container">
    <div id="team" class="header">The Team</div>
    <div class="wraper">
      <div class="wraper1">
        <div class="richard-hendricks">
          <div>
            <img class="img" src="./img/1.png" alt="richard-hendricks" />
          </div>
          <div class="name">Richard Hendricks</div>
          <div class="job">Founder & CEO</div>
        </div>
        <div class="dinesh-chugtai">
          <div>
            <img class="img" src="./img/2.png" alt="dinesh-chugtai" />
          </div>
          <div class="name-dinesh">Dinesh Chugtai</div>
          <div class="job">Senior Programmer</div>
        </div>
        <div class="bertram-gilfoyle">
          <div>
            <img class="img" src="./img/3.png" alt="bertram-gilfoyle" />
          </div>
          <div class="name-bertram">Bertram Gilfoyle</div>
          <div class="job">Chief Systems Architect</div>
        </div>
      </div>
      <div class="wraper2">
        <div class="jared-dunn">
          <div>
            <img class="img" src="./img/4.png" alt="jared-dunn" />
          </div>
          <div class="name-jared">Jared Dunn</div>
          <div class="job">Chief Operating Officer</div>
        </div>
        <div class="monica-hall">
          <div>
            <img class="img" src="./img/5.png" alt="monica-hall" />
          </div>
          <div class="name-monica">Monica Hall</div>
          <div class="job">Chief Financial Officer</div>
        </div>
        <div class="nelson-bighetti">
          <div>
            <img class="img" src="./img/6.png" alt="nelson-bighetti" />
          </div>
          <div class="name-nelson">Nelson Bighetti</div>
          <div class="job">Majority Investor</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  width: 100%;
  height: 845px;
  background: #eeeeee;
}

.wraper {
  width: 50%;
  margin-left: auto;
  margin-right: auto;
  margin-top: 32px;
}

.wraper1 {
  display: flex;
  margin-left: 55px;
}

.wraper2 {
  display: flex;
  margin-left: 55px;
}

.header {
  font-style: normal;
  font-weight: 500;
  font-size: 64px;
  line-height: 75px;
  text-align: center;
  color: #007765;
  padding-top: 58px;
}

.richard-hendricks {
  width: 350px;
  height: 283px;
}

.dinesh-chugtai {
  width: 350px;
  height: 283px;
}

.bertram-gilfoyle {
  width: 350px;
  height: 283px;
}

.jared-dunn {
  width: 350px;
  height: 283px;
}

.monica-hall {
  width: 350px;
  height: 283px;
}

.nelson-bighetti {
  width: 350px;
  height: 283px;
}

.img {
  width: 50%;
  height: 50%;
  margin-left: 17px;
}

.name {
  width: max-content;
  font-style: normal;
  font-weight: 700;
  font-size: 24px;
  line-height: 28px;
  color: #007765;
}

.name-dinesh {
  width: max-content;
  font-style: normal;
  font-weight: 700;
  font-size: 24px;
  line-height: 28px;
  color: #007765;
  margin-left: 26px;
}

.name-bertram {
  width: max-content;
  font-style: normal;
  font-weight: 700;
  font-size: 24px;
  line-height: 28px;
  color: #007765;
  margin-left: 18px;
}

.name-jared {
  width: max-content;
  font-style: normal;
  font-weight: 700;
  font-size: 24px;
  line-height: 28px;
  color: #007765;
  margin-left: 38px;
}

.name-monica {
  width: max-content;
  font-style: normal;
  font-weight: 700;
  font-size: 24px;
  line-height: 28px;
  color: #007765;
  margin-left: 38px;
}

.name-nelson {
  width: max-content;
  font-style: normal;
  font-weight: 700;
  font-size: 24px;
  line-height: 28px;
  color: #007765;
  margin-left: 20px;
}
.job {
  width: max-content;
  font-style: italic;
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
  color: #000000;
  margin-left: 25px;
}

@media (max-width: 1327px) {
  .wraper {
    width: 75%;
  }
}

@media (max-width: 963px) {
  .container {
    height: 725px;
  }
  .wraper {
    width: 75%;
  }
}

@media (max-width: 815px) {
  .container {
    height: 645px;
  }
  .header {
    font-weight: 500;
    font-size: 43px;
    line-height: 58px;
  }
  .wraper {
    width: 75%;
  }

  .img {
    width: 50%;
    height: 50%;
    margin-left: 30px;
  }

  .name {
    font-weight: 700;
    font-size: 17px;
    line-height: 21px;
  }

  .name-dinesh {
    font-weight: 700;
    font-size: 17px;
    line-height: 21px;
    margin-left: 26px;
  }

  .name-bertram {
    font-weight: 700;
    font-size: 17px;
    line-height: 21px;
    margin-left: 18px;
  }

  .name-jared {
    font-weight: 700;
    font-size: 17px;
    line-height: 21px;
    margin-left: 38px;
  }

  .name-monica {
    font-weight: 700;
    font-size: 17px;
    line-height: 21px;
    margin-left: 38px;
  }

  .name-nelson {
    font-weight: 700;
    font-size: 17px;
    line-height: 21px;
    margin-left: 20px;
  }

  .job {
    font-weight: 400;
    font-size: 14px;
    line-height: 18px;
    margin-left: 25px;
  }
}

@media (max-width: 734px) {
  .container {
    height: 645px;
  }
  .wraper {
    width: 100%;
  }

  .richard-hendricks {
  width: 350px;
  height: 183px;
}

.dinesh-chugtai {
  width: 350px;
  height: 183px;
}

.bertram-gilfoyle {
  width: 350px;
  height: 183px;
}

.jared-dunn {
  width: 350px;
  height: 183px;
}

.monica-hall {
  width: 350px;
  height: 183px;
}

.nelson-bighetti {
  width: 350px;
  height: 183px;
}
}

@media (max-width: 546px) {
  .container {
    height: 545px;
  }
  .wraper1 {
    display: flex;
    margin-left: 1px;
  }
  .wraper2 {
    display: flex;
    margin-left: 1px;
  }

  .richard-hendricks {
  width: 350px;
  height: 183px;
}

.dinesh-chugtai {
  width: 350px;
  height: 183px;
}

.bertram-gilfoyle {
  width: 350px;
  height: 183px;
}

.jared-dunn {
  width: 350px;
  height: 183px;
}

.monica-hall {
  width: 350px;
  height: 183px;
}

.nelson-bighetti {
  width: 350px;
  height: 183px;
}

  .img {
    width: 50%;
    height: 50%;
    margin-left: 20px;
  }

  .name {
    font-weight: 500px;
    font-size: 12px;
    line-height: 17px;
    margin-left: 10px;
  }

  .name-dinesh {
    font-weight: 500;
    font-size: 12px;
    line-height: 17px;
    margin-left: 15px;
  }

  .name-bertram {
    font-weight: 500;
    font-size: 12px;
    line-height: 17px;
    margin-left: 15px;
  }

  .name-jared {
    font-weight: 500;
    font-size: 12px;
    line-height: 17px;
    margin-left: 20px;
  }

  .name-monica {
    font-weight: 500;
    font-size: 12px;
    line-height: 17px;
    margin-left: 25px;
  }

  .name-nelson {
    font-weight: 500;
    font-size: 12px;
    line-height: 17px;
    margin-left: 15px;
  }

  .job {
    font-weight: 400;
    font-size: 10px;
    line-height: 14px;
    margin-left: 15px;
  }
}
</style>
