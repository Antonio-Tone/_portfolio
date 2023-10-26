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
  background: radial-gradient(circle 248px at center, #16d9e3 0%, #30c7ec 47%, #46aef7 100%);
  color: #FFFF; 
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
