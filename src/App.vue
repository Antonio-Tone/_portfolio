<template>
  <navbarComp/>
  <router-view/>
</template>
<script>
import navbarComp from "./components/navbarComp.vue";
export default{
  components: {navbarComp}
}
</script>

<style>

#app,html {
  color: #FFFF; 
  overflow-x: hidden;
  background: radial-gradient(circle at 10% 20%, rgb(69, 86, 102) 0%, rgb(34, 34, 34) 90%); 
}
html::-webkit-scrollbar{
  display: none !important;
}

nav {
  padding: 30px;
  z-index: 999 !important;
  padding: 0 !important;
}

nav a {
  font-weight: bold;
  color: white;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
