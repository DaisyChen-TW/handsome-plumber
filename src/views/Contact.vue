<template>

<div class="containers">  
  <Sidebar />
  <div class="about">
    <h2>聯絡電話</h2>
    <div class="tel">0912-345-678</div>
  </div>
</div>
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
.tel {
  font-size: 100px;
  margin-top: 200px;
  font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
}
</style>