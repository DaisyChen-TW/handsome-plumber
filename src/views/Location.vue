<template>

<div class="containers">  
  <Sidebar />
  <div class="about">
    <h2>服務處</h2>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d804.7116048484953!2d121.45985209450603!3d24.98081667536989!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x346802c449d62ad7%3A0xd89542220b92af9b!2z5LuB5oSb56S-5Y2A5YWs5ZyS!5e0!3m2!1szh-TW!2stw!4v1649447088527!5m2!1szh-TW!2stw" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    <h2>服務範圍在土城與板橋</h2>
    <h2>其他地區請來電詳談和預約</h2>
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
</style>