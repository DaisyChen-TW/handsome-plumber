<template>
<div class="container">
  <div class="sidebar">
    <a class="link" href="">簡介</a>
    <a class="link" href="">服務</a>
    <!-- <a class="link" href="">水電小知識</a> -->
    <a class="link" href="">服務範圍</a>
    <a class="link" href="">零件超市</a>
    <a class="link" href="">水電諮詢</a>
    <a class="link" href="">案例分享</a>
    <a class="link" href="">我要預約</a>
  </div>
</div>
</template>

<style scoped>
.container {
  height: 100vh;
  width: 13vw;
  /* min-width: 150px; */
  padding: 10px;
  position: fixed;
  /* border: 2px solid red; */
}
.sidebar {
  /* position: fixed; */
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  height: 400px;
}
.link {
  /* border-radius: 20px; */
  height: 36px;
  line-height: 36px;
  text-decoration: none;
  color: 	#483C32;
  font-size: 18px;
}
.link:hover {
  color: whitesmoke; 
   background: #8B4513;
}
</style>