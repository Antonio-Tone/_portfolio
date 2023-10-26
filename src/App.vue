<template>
  <nav class="d-flex justify-content-center">
    <ul class="ms-auto">
      <il><router-link to="/">Home</router-link></il>
      <il> <router-link to="/about">About</router-link></il>
    </ul>
  </nav>
  <router-view/>
</template>

<style>
*,#app {
  background: radial-gradient(circle 248px at center, #16d9e3 0%, #30c7ec 47%, #46aef7 100%);

  color: #2c3e50; 
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
