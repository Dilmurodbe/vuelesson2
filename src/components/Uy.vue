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
    <Bosh />
    <img class="home-img" src="../assets/img/three.png" alt="" />
  </div>
  <div class="container">
    <div class="row">
      <div class="col-12 col-lg-6">
      <div class="text">

        <h1>
          Woocommerce <br> Bonus Point
        </h1>
        <div class="text-button">
          <p>
            The plugin provides a thoughtful and fully customizable bonus system for your online store. This is the real magic in the fight to attract and retain customers and the desire to shop in your online store again and again.
          </p>
        </div>
        <div class="mt-5">
          <Button class="header-button" name="Choose Your Plan" />
          <p class="uy-button-p"><span>Or</span>  try the free version</p>
        </div>
        </div>
      </div>
      <div class="col-12 col-lg-6 pt-150px">
        <img class="img-savat" src="../assets/img/savat.png" alt="">
      </div>
   <div class="col-3">
    <img class="imgnum" src="../assets/img/90num.png" alt="">
    <p class="num-p">Websites increased sales</p>
   </div>
   <div class="col-3">
    <img class="imgnum" src="../assets/img/100num.png" alt="">
    <p class="num-p">Support and blog articles</p>
   </div>
   <div class="col-3">
    <img class="imgnum" src="../assets/img/90num.png" alt="">
    <p class="num-p">Five stars review</p>
   </div>
   <div class="col-3">
    <img class="imgnum" src="../assets/img/100num.png" alt="">
    <p class="num-p">Increase in repeat customers</p>
   </div>
    </div>
  </div>
</template>
<style>
.num-p{
  font-family: 'Raleway';
font-style: normal;
color: #fff;
font-size: 24px;
}
.imgnum{
  width: 50%;
  height: auto;
}
.img-savat{
  width: 100%;
  height: auto;
}
.pt-150px{
  padding-top: 150px;
}
.uy-button-p{
  margin-top: 2 5px;
  font-family: 'Raleway';
font-style: normal;
font-size: 24px;
color: rgb(31, 156, 31);
}
.uy-button-p span{
  font-family: 'Raleway';
font-style: normal;
font-size: 24px;
color: rgb(200, 199, 199);
}
.home {
  display: flex;
  position: relative;
  width: 100%;
}
.home-img {
  width: 100%;
  height: 1000px;
background-color: black;
  object-fit: cover;
  position: absolute;
  z-index: -1;
}
.text {
  width: 65%;
  padding-top: 150px;
  height: auto;
  
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
  width: 48%;
  color: #fff;
}
.p15 {
  font-size: 15px;
  color: #fff;
  text-decoration: underline;
}
.header-button {
  background: 
green;
  border-radius: 7px;
  border: none;
  font-size: 18px;
  color: #000000;
  padding: 30px 60px;
  margin-bottom: 0rem;
}
</style>
