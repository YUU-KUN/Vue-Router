<template>
  <div id="app">
    <ul class="nav" style="background-color: #2abd7a">
      <li class="nav-item">
        <router-link class="nav-link" to="/">Home</router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="/about">About</router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="/contact">Contact</router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="/notFound">Not Found</router-link>
      </li>
    </ul>

    <router-view></router-view>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
ul {
  justify-content: center;
}
.nav-link {
  color: white;
}
.nav-link:hover {
  color: green;
}
</style>
