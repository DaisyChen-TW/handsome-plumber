<template>

<div class="containers">  
  <Sidebar />
  <div class="about">
    <h2>阿羅哈～今天是個愉快的一天！</h2>
    <!-- <img src="../assets/dodo.jpg" alt="">
    <img src="../assets/a-pin.png" alt="" class="a-pin"> -->
    <img src="../assets/plumber.png" alt="">
    <h3>大家好，我是阿平，一名職業水管管路安裝師傅</h3>
    <h3>擅長水電與居家裝修</h3>
    <h3>擁有多年經驗且認真負責</h3>
    <h3>夢想是成立自己的工作室，協助大家達成夢想家的願景。</h3>
  </div></div>
</template>
<script>
import Sidebar from '@/components/Sidebar.vue'

export default {
  name: 'Home',
  components: {
    Sidebar,
  }
}
</script>
<style scoped>
/* .containers {
  display: grid;
  grid-template-columns: 20% 80%;
  max-width: 1500px;
  margin: 0 auto;
  padding: 0 20px;
} */
.about {
  border: 2px solid rgb(236, 233, 233);
  margin-left: 175px;
  height: 100vh;
}
.a-pin {
  width: 500px;
  height: 350px;
}
</style>