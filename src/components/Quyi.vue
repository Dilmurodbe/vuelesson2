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
<div class="quyi1">
  <div class="container">
    <div class="row">
      <div class="col-6">
        <p class="p64">After a month of working with us</p>
      </div>    </div>
        </div>
    </div>
      <div class="quyi2">
        <div class="container">
          <div class="row">

         
        <div class="div">
  <div class="col-5 m-5">
  <p class="p64-blue">Save over 40% with plugins Bundle</p>
  <p class="p24">Buy a plugin right now and save 40% of the tariff cost</p>
  <Button class="button-quyi" name="Get started" />
</div></div>
</div>
        </div>
        <div class="quyi-div">
       <img class="logo" src="../assets/img/UpSells.png" alt="">
       <a class="bosh-h1"  href="">Features </a>
       <a class="bosh-h1" href="">Documentation</a>
       <a class="bosh-h1" href="">Support</a>
       <a class="bosh-h1" href="">+7-999-322-23-32</a>
       <a class="bosh-h1" href="">asda@mail.ru</a>

       
        
       
     
      
  </div>
</div>

</template>
<style>
.bosh-button{
  font-family: 'Inter';
font-style: normal;
font-size: 18px;
color: rgb(255, 255, 255);
background-color: black;
padding: 0px 10px;
margin-left: 23%;

}
.bosh-button1{
  font-family: 'Inter';
font-style: normal;
font-size: 18px;
color: rgb(0, 0, 0);
background-color: rgb(255, 255, 255);
padding: 10px 20px;
}
.quyi-div{
border: 10px solid rgba(2, 14, 12, 0.01);
border-bottom-color: rgba(2, 14, 12, 0.01) ;
border-left-color: rgba(2, 14, 12, 0.01) ;
background: rgba(2, 14, 12, 0.01);
backdrop-filter: blur(20px);
border-radius: 0px 0px 0px 10px;
margin-top:130px ;
margin-bottom: 50px;
}

.logo {
    width: 75px;
    height: 29px;
    margin: 0 50px;
}

.bosh-h1 {
  font-size: 16px;
  color: rgb(255, 255, 255);
  margin: 0 50px;
  text-decoration: none;
}
.button-quyi{
  background: #1EEBCD;
  background-repeat: 10px;
  font-size: 18px;
  color: black;
  padding: 30px 150px;
}
.p24{
  font-family: 'Raleway';
font-style: normal;
color: #fff;
font-size: 24px;
}
.p64-blue{
  font-family: 'Raleway';
font-style: normal;
color: #1EEBCD;
font-size: 64px;
}
.div{
margin-top: -1px;
  width: 100%;
  height: auto;
  background: url(../assets/img/div.png) no-repeat center center / cover;
  background-color: black;
}
.p64{
font-size: 64px;
color: #fff;
}
.quyi1{
  width: 100%;
  height: auto;
  background-color: black;
}
.quyi2{
  width: 100%;
  height: auto;
  
  background: url(../assets/img/quyi.png) no-repeat center center / cover;
  background-color: black;
}
</style>
