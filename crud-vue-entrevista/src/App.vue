<template >
  <nav class="navbar navbar-expand navbar-light bg-light">
    <div class="nav navbar-nav">
    <router-link to="/" class="nav-link">Home</router-link>
    <router-link to="/listar" class="nav-link">Empleados</router-link>
    </div>
  </nav>
  <br/>
  <router-view />
</template>
<style>
  #app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: aqua;
  min-height: 500vh;
}
</style>

