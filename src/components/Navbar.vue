<script>
export default {
  name: 'NavbarPage'
}
</script>
<template>
  <div class="container">
    <div class="row">
<div class="d-flex justify-content-between">
    
<div class="col-auto mt-5 ">
  <div class="navbar-left">
  <div class="d-flex justify-content-around">
  <img class="logo" src="../assets/img/Group 88.png" alt="">
<a class="navbar-h1" href="">Azur Life</a>
<img src="../assets/img/Vector 44.png" alt="">
<a class="navbar-h1" href="" ><img src="../assets/img/Exclude.png" alt="">  Франция, бульвар Леклерк, 46, 06310, Болье-сюр-Мер
</a><img src="../assets/img/Vector 44.png" alt="">


<a class="navbar-h1" href=""> <img src="../assets/img/Vector.png" alt="">    +33 4 93 16 06 31</a>
</div>
</div>
</div>

<div class="col-auto mt-5">
  <a class="navbar-language-changer-en" href="">en</a>
  <a class="navbar-language-changer" href="">fr</a>
  <a class="navbar-language-changer" href="">ru</a>
  <a class="navbar-language-changer" href="">it</a>
</div>
</div>
  </div></div>
</template>

<style>
.logo{
  width: 25px;
  height: 20px;
 margin: 0 15px;
}

.navbar-h1{
  font-size: 16px;
  color: rgb(255, 255, 255);
  margin: 0 15px;
   text-decoration: none;
}
.navbar-language-changer-en{
  font-size: 15px;
  color: #fff;
  text-decoration: underline;
  margin: 0 10px;

}

.navbar-language-changer{
  font-size: 15px;
  color: #fff;
  margin: 0 10px;
  text-decoration: none;
}

</style>
