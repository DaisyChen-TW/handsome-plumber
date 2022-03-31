<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <Header />
  <Sidebar />
  <Introduction />

</template>

<script>
import Header from './components/Header.vue'
import Sidebar from './components/Sidebar.vue'
import Introduction from './components/Introduction'

export default {
  name: 'App',
  components: {
    Header,
    Sidebar,
    Introduction
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
/*reset */
html {
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: inherit;
}

body,
h1,
h2,
h3,
h4,
h5,
h6,
p,
ol,
ul,
menu {
  margin: 0;
  padding: 0;
  font-weight: normal;
}

table {
  border: none;
  border-spacing: 0;
  border-collapse: collapse;
}

th,
td {
  text-align: initial;
}

/*reset end*/

</style>
