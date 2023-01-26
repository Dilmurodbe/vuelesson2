<script>
import Bosh from "./Bosh.vue";
import Button from "./Button.vue";
export default {
  name: "app",

  data() {
    return {
      count: 0,
    };
  },

  components: {
    Bosh,
    Button,
  },
};
</script>
<template>
  <div class="home">
    <Navbar />
    <img class="home-img" src="../assets/img/header.png" alt="" />
  </div>
  <div class="container">
    <div class="row">
      <div class="text">
        <p class="header-p-12">Главная страницы > О нас</p>

        <h1>
          Сделки <br />
          на русском языке <br />
          Вашей недвижимостью <br />
          во Франции <br />
          2017 года
        </h1>
        <div class="text-button">
          <p>
            Открываем новые горизонты Франции для Вас.  Мы подберем недвижимость
            исходя из озвученных запросов, обеспечим управление вашими
            апартаментами или окажем услугу консьерж-сервиса, а вам остается
            только одно: наслаждаться жизнью.
          </p>
        </div>
        <div class="mt-5">
          <Button class="header-button" name="Напишите нам" />
        </div>
      </div>
    </div>
  </div>
</template>
<style>
@media (max-width: 1199px) {
  .home {
    display: flex;
    position: relative;
    width: 100%;
  }
  .text h1 {
    font-family: "Playfair Display";
    font-style: normal;
    font-weight: 400;
    font-size: 52px;
    line-height: 90%;
    color: #fff;
  }
}
@media (max-width: 991px) {
}
@media (max-width: 767px) {
}

@media (max-width: 575px) {
}
.home {
  display: flex;
  position: relative;
  width: 100%;
}
.home-img {
  width: 100%;

  object-fit: cover;
  position: absolute;
  z-index: -1;
}
.text {
  width: 65%;
  padding-top: 150px;
}
.header-p-12 {
  font-family: "Manrope";
  font-style: normal;
  font-size: 12px;
  line-height: 160%;
  color: rgba(255, 255, 255, 0.6);
  margin-top: -90px;
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
