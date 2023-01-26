<script>
import Navbar from "./navbar.vue";
import Button from "./Button.vue";
export default {
  name: "app",

  data() {
    return {
      count: 0,
    };
    
  },

  components: {
    Navbar, Button
  },
};
</script>
<template>
  <div class="home">
    <Navbar />
    <img class="home-img" src="../assets/img/home.jpg" alt="" />
  </div>
  <div class="container">
    <div class="row">
      <div class="text">
        <h1>
          Подбор <br />
          недвижимости <br />
          с полным сопровождением <br />
          на Вашем языке
        </h1>
        <div class="text-button">
          <p>
            Наше агентство специализируется на премиум объектах и презентует их
            Вам на русском языке. Подбор недвижимости во всей Франции с фокусом
            на самых привилегированных и живописных районах Французского
            Средиземноморья - Ницца, Канны или Лазурный Берег без лишних
            временных затрат и наценнок.
          </p>
        </div>
      </div>
      <div class="d-flex justify-content-between mt-5">
        <p class="p15">Скачать презентацию</p>

        <Button class="header-button" name="Напишите нам" />
      </div>
    </div>
  </div>
</template>
<style>
.home {
  display: flex;
  position: relative;
}
.home-img {
  width: 100%;

  object-fit: cover;
  position: absolute;
  z-index: -1;
}
.text {
  width: 65%;
  padding-top: 200px;
}

.text h1 {
  font-family: "Playfair Display";
  font-style: normal;
  font-weight: 400;
  font-size: 71px;
  line-height: 90%;
  color: #fff;
}
.text-button {
  width: 53%;
  color: #fff;
}
.p15 {
  font-size: 15px;
  color: #fff;
  text-decoration: underline;
}
.header-button {
  background: #fff9ec;
  border-radius: 7px;
  border: none;
  font-size: 15px;
  color: #be7e00;
  padding: 15px;
  margin-bottom: 0rem;
}


</style>
