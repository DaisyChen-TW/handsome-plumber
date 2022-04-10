<template>
<Sidebar />
<Container>
  <div class="service">
    <h1>服務項目</h1>
    <div class="topics">
      <div class="topic">燈具安裝</div>
      <div class="topic">衛浴裝修</div>
      <div class="topic">居家修繕</div>
    </div>
    <h2></h2>
  </div>
  </Container>
</template>
<script>
import Sidebar from '@/components/Sidebar.vue'
import Container from '@/components/Container.vue'

export default {
  name: 'Service',
  components: {
    Sidebar,
    Container
  }
}
</script>
<style scoped>
.service {
  border: 2px solid rgb(236, 233, 233);
  margin-left: 175px;
  height: 100vh;
}
.topics {
  display: flex;
  justify-content: space-evenly;
  margin-top: 250px;
}
.topic {
  width: 250px;
  height: 270px;
  border-radius: 10px;
  border: 2px solid #E5E4E2;
  line-height: 270px;
  font-size: 26px;
}
.topic:hover {
  border: 1px solid grey;
  border-radius: 10px;
}
</style>