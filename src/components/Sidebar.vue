<template>
<div class="container">
  <div class="sidebar">
    <div class="brand-name">#阿平水電</div>
    <div class="link-group">
    <router-link to="/about" class="link" href=""> 
      <div class="icon">
        <img class="intro-icon" src="../assets/internet.png" alt="">簡介
      </div>
    </router-link>
    <router-link to="/service" class="link" href=""><div class="icon">
        <img class="intro-icon" src="../assets/star.png" alt="">服務
        <!-- <div class="name"></div> -->
      </div></router-link>
    <!-- <a class="link" href="">水電小知識</a> -->
    <router-link to="/location" class="link" href=""><div class="icon">
        <img class="intro-icon" src="../assets/map-location.png" alt="">服務範圍
        <!-- <div class="name"></div> -->
      </div></router-link>
    <!-- <a class="link" href="">零件超市</a>
    <a class="link" href="">水電諮詢</a>
    <a class="link" href="">案例分享</a> -->
    <router-link to="/contact" class="link" href=""><div class="icon">
        <img class="intro-icon" src="../assets/calendar.png" alt="">我要預約
        <!-- <div class="name"></div> -->
      </div></router-link>
    </div>

  </div>
</div>
</template>

<style scoped>
.container {
  height: 100vh;
  /* width: 20vw; */
  /* min-width: 150px; */
  padding: 10px;
  position: fixed;
  /* border: 2px solid red; */
  background: #fff;
}
.brand-name {
  font-size: 26px;
  font-weight: 500;
  border-radius: 5px;
  height: 40px;
  line-height: 40px;
  letter-spacing: 3px;
  padding: 10px;
  /* border: 2px solid #483C32; */
}
.link-group {
  /* position: fixed; */
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  height: 300px;
}
.link {
  /* border-radius: 20px; */
  height: 36px;
  line-height: 36px;
  text-decoration: none;
  color: 	#483C32;
  font-size: 18px;
  text-align: center;
  /* display: flex; */
}
.link:hover {
  color: black; 
   background: rgb(236, 233, 233);
}
.icon {
  display: flex;
  height: 36px;
  align-items: center;
}
.intro-icon {
  width:20px;
  height: 20px;
  vertical-align: middle;
  /* border: 1px solid red; */
  margin-right: 20px;
  padding-left: 20px;
  /* text-align: center; */
  /* margin-left: 10px; */
}
</style>