<script>
export default {
  name: "Navbar",
  data() {
    return {
      showmenu: false,
    };
  },
  methods: {
    showfunction() {
      this.showmenu ? (this.showmenu = false) : (this.showmenu = true);
      console.log(this.showmenu);
    },
  },
};
</script>
<template>
  <div class="container">
    <div class="row">
      <div class="d-flex justify-content-between">
        <div class="col-auto mt-5">
          <div class="navbar-left">
            <div class="d-flex justify-content-around">
              <img class="logo" src="../assets/img/Group 88.png" alt="" />
              <a class="navbar-h1" href="">Azur Life</a>
              <img src="../assets/img/Vector 44.png" alt="" />
              <a class="navbar-h1 dnone" href=""
                ><img src="../assets/img/Exclude.png" alt="" /> Франция, бульвар
                Леклерк, 46, 06310, Болье-сюр-Мер </a
              ><img src="../assets/img/Vector 44.png" alt="" />

              <a class="navbar-h1 m-320" href="">
                <img src="../assets/img/Vector.png" alt="" /> +33 4 93 16 06
                31</a
              >
            </div>
          </div>
        </div>

        <div class="col-auto mt-5">
          <a class="navbar-language-changer-en" href="#">en</a>
          <a class="navbar-language-changer" href="#">fr</a>
          <a class="navbar-language-changer" href="#">ru</a>
          <a class="navbar-language-changer" href="#">it</a>
          <a class="navbar-language-changer" href="#" @click="showfunction">
            <img src="../assets/img//Group 41.png" alt=""
          /></a>
          <div
            class="menubar"
            :style="{ visibility: showmenu ? 'visible' : 'hidden' }"
          >
            <div class="lists">
              <div class="close">
                <h1 @click="showfunction">close</h1>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.logo {
  width: 25px;
  height: 20px;
  margin: 0 15px;
}

.navbar-h1 {
  font-size: 16px;
  color: rgb(255, 255, 255);
  margin: 0 15px;
  text-decoration: none;
}
.navbar-language-changer-en {
  font-size: 15px;
  color: #fff;
  text-decoration: underline;
  margin: 0 10px;
}

.navbar-language-changer {
  font-size: 15px;
  color: #fff;
  margin: 0 10px;
  text-decoration: none;
}

.lists {
  background: #fff;
}
</style>
