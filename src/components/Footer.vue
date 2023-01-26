<script>
import Button from './Button.vue';
export default {
  name: "app",

  data() {
    return {
      count: 0,
    };
  },

  components: {
    Button
  },
};
</script>
<template>
  <div class="footer">
    <div class="container">
      <div class="row">
        <div class="col-12  col-lg-4 d-flex flex-column">
          <div class="footer-div">
          <p class="footer-p">Перезвоните мне</p>
          <input class="name" type="text" placeholder="Имя">
          <input class="name" type="text" placeholder="Телефон">
          <input class="name" type="text" placeholder="Email">
          <div class="mt-5">
        <Button class="footer-button-basic" name="Отправить запрос" /></div>
          <div class="footer-button">
          <a href=""> <img class="phone" src="../assets/img/phone.png" alt=""> +33 4 93 16 06 31</a> <img class="app" src="../assets/img/instagram.png" alt="">
          <img class="app" src="../assets/img/facebook.png" alt="">
          <br>
          <a href=""> <img class="phone" src="../assets/img/email.png" alt=""> contact@azur-life.com</a> <br>

          <a href=""> <img class="phone" src="../assets/img/locatin.png" alt=""> Франция, бульвар Леклерк, 46, 06310, Болье-сюр-Мер
</a> <br>
        </div></div></div>
        <div class="col-sm-3 col-lg-4 dnone">
          <p class="footer-p">Навигация</p> 
          <li><a class="footer-a" href="">О нас </a> <br></li>
            <li>  <a class="footer-a" href="">Все объекты </a> <br></li>
              <li> <a class="footer-a" href="">Продажа </a><br></li>
                <li> <a class="footer-a" href="">Аренда </a><br></li>
                  <li> <a class="footer-a" href="">Купить,  продать, арендовать с нами </a> <br></li>

                    <li> <a class="footer-a" href="">Презентация </a> <br></li>
                      <li> <a class="footer-a" href="">Экспертная оценка </a> <br></li>
                        <li>  <a class="footer-a" href="">Управление недвижимостью </a><br></li>
                          <li>   <a class="footer-a" href="">Консьерж-сервис </a>  <br></li>

                            <li class="li-span"> <a class="footer-a" href="">Наша комиссия </a> <br></li>

                              <li class="li">  <a class="footer-a" href="">Политика конфиденциальности </a><br></li>

        </div>
        <div class="col-sm-3 col-lg-3 dnone">
          <p class="footer-p">Регионы</p> 
          <li>
          <a class="footer-a" href="">Апартаменты в Больё-сюр-Мер</a> <br></li>
          <li> <a class="footer-a" href="">Вилла в Больё-сюр-Мер </a> <br></li>
         <li><a class="footer-a" href="">Вилла в Эзе </a><br></li>
         <li><a class="footer-a" href="">Вилла в Сен-Жан-Кап-Ферра</a><br></li>
         <li><a class="footer-a" href="">Апартаменты в Эзе </a> <br></li>

         <li class="footer-li"><a class="footer-a" href="">Апартаменты в Сен-Жан-Кап-Ферра </a> <br></li>
          

          

        </div>
      </div>
    </div>
  </div>

</template>
<style>

.app{
  width: auto;
  height: auto;
  margin: 0px 10px 0px 0px;
}
.phone{
  margin: 0px 8px 0px 0px;
}
.footer-div{
  width: 70%;
  height: auto;
}
.footer-button{
  margin-top: 163px;
}
li{
  margin: 25px 0px;
}
.li{
  margin: 85px 0px;
}
.li-span{
  margin: -30px 0px;
}
.footer-li{

 margin-top: 276px;

}
.footer-a{
  color: #fff;
  text-decoration: none;
font-family: 'Manrope';
font-style: normal;
font-size: 16px;
list-style: none;
}
.footer{
  width: 100%;
 padding-top: 100px;
  height: auto;
  background: url(../assets/img/footer-background.png) no-repeat center center / cover;
background-color: black;
}
.footer-p{
  font-family: 'Manrope';
font-style: normal;
font-size: 20px;
color: #fff;
list-style: none !important;
}
.name{
  border: none;
  color: rgb(102, 102, 103);
  font-family: 'Manrope';
font-style: normal;
font-size: 15px;
background-color: black;
margin: 15px 0px;
}
.footer-button-basic{
  border: none;
  border-radius: 7px;
  padding: 15px;
  background-color: rgb(240, 200, 146);
  font-size: 16px;
  text-align: right;
  text-decoration: underline;
  color: white;
}

</style>
