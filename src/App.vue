<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view />
</template>

<style lang="scss">
body {
  margin: 0;
  height: 100vh;
}
#app {
  padding: 0;
  margin: 0;
  height: 100%;
  background: #00021e;
}
</style>
