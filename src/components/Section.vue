<script>
import Button from "./Button.vue";

export default {
  name: "app",

  data() {
    return {
      count: 0,
    };
  },

  components: {
  Button,
 
  },
};
</script>
<template>
  
  <div class="Section">
    <div class="container">
      <div class="row">
        <div class="d-flex justify-content-center">
          <div class="section-div">
            <img class="section-div-img" src="../assets/img/Frame.png" alt="" />
            <p class="section-div-p">
              “Состоятельные люди приезжают на Лазурный берег за спокойствием и
              даже уединением”
            </p>
            <p class="section-div-p-button">Forbes</p>
          </div>
        </div>
      </div>
    </div>
  </div>
 
  <div class="section-middle">
    <div class="container">
      <div class="row">
        <div class="col-12 col-lg-6">
          <p class="section-middle-p">Специалисты Azur Life</p>
        </div>
        <div class="col-12 col-lg-6 row">
          <img
            class="section-middle-img"
            src="../assets/img/women.png"
            alt=""
          />
          <img
            class="section-middle-img2"
            src="../assets/img/girl.png"
            alt=""
          />
        </div>
      </div>
    </div>
  </div>
  <Slide/>
  <div class="section-buttom">
    <div class="container">
      <div class="row">
        <div class="col-12 col-lg-6">
          <h1 class="section-buttom-p">Экспертиза 
агентства </h1>
<p class="section-buttom-p-little">Azur Life - динамично развивающееся агентство, отстаивающее ценности конфиденциальности, лояльности, высокого профессионализма и индивидуального подхода с 2017 года. Мы имеем все необходимые лицензии, страховые и финансовые гарантии, требуемые французским законодательством для того, чтобы провести Вашу сделку по недвижимости максимально качественно и комфортно.</p>
<div class="col-numbers">
            <div class="col-number">
              <p class="col-number-title">7</p>
              <p class="col-number-title-info">лет на рынке</p>
            </div>
            <div class="col-number">
              <p class="col-number-title">27</p>
              <p class="col-number-title-info">постоянных клиентов</p>
            </div>
            <div class="col-number">
              <p class="col-number-title">240</p>
              <p class="col-number-title-info">сделок с недвижимостью</p>
            </div>
          </div>
<div class="mt-5">
        <Button class="section-buttom-button" name="Купить или продать с нами" /></div>
        </div>
        <div class="col-12 col-lg-6">
          <img class="img" src="../assets/img/women1.png" alt="">
        </div>
        <div class="d-flex justify-content-between mt-5">
          <p class="buttom-p"> Вернуться на главную страницу</p>
          <p class="buttom-p">Все объекты ></p>
        </div>
      </div>
      
    </div>
  </div>
  
</template>
<style>


.img{
  width: 100%;
  height: auto;
}
.col-numbers {
  display: flex;
  justify-content: space-between;
  text-align: center;
  width: 80%;
}

.col-number-title {
  font-family: Playfair Display;
  font-size: 85px;
  font-weight: 400;
  line-height: 76px;
  text-align: center;
  letter-spacing: -0.02em;
  color: #fffbf2;
  
}
.col-number-title-info{
  width: 98px;
  font-family: 'Manrope';
font-style: normal;
color: #ffffff;
font-size: 12px;
}
  .buttom-p{
    font-family: 'Manrope';
font-style: normal;
font-size: 20px;
color: #FFFFFF;
  }
  .buttom-p:hover{
    font-family: 'Manrope';
font-style: normal;
font-size: 20px;
color: #FFFFFF;
text-decoration: underline;
  }
.section-buttom-button{
  background: #323232;
  border-radius: 7px;
  font-family: 'Manrope';
font-style: normal;
font-size: 15px;
color: #FFFFFF;
padding: 18px;
}
.section-buttom{
  width: 100%;
  height: auto;
  background-color: #101010;
  padding-top: 300px;
}
.section-buttom-p-little{
  width: 409px;
font-family: 'Manrope';
font-style: normal;
font-size: 15px;
color: #FFFFFF;

}
.section-buttom-p{
  width: 479px;
font-family: 'Playfair Display';
font-style: normal;
font-size: 84.9577px;
color: #FFFFFF
}
.section-middle-img {
  width: 80%;
  height: auto;
  margin-top: 65px;
  position: relative;
}
.section-middle-img2 {
  width: 20%;
  height: auto;
  position: absolute;
  margin-top: 30%;
  margin-left: -17%;
}
.section-middle {
  width: 100%;
  height: auto;
  background-color: #101010;
}
.section-middle-p {
  width: 538px;
  font-family: "Playfair Display";
  font-style: normal;
  letter-spacing: -0.02em;
  font-size: 84.9577px;
  color: #ffffff;
  margin-bottom: none !important;
}
.section-div-img {
    width: auto;
    position: relative;
    left: 37%;
    top: 29% !important;
}
.section-div {
  position: absolute;
  width: 85%;
  height: 61  0px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: -10%;
  background: #fffbf2;
  flex-direction: column;
}
.Section {
  width: 100%;
  height: 500px;
  margin-top: 18%;
  background: url(../assets/img/section-background.png);
  background-color: #101010;
}
.section-div-p {
  width: 74%;
  font-family: "Playfair Display";
  font-style: normal;
  font-size: 62px;
  margin-bottom: none !important;
  text-align: center;
  color: #101010;
}
.section-div-p-button {
  width: 70%;
  font-family: "Manrope";
  font-style: normal;
  font-size: 24px;

  text-align: center;

  margin-bottom: none;
  color: #101010;
}

</style>
