<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/student">student</router-link> |
      <router-link to="/teacher">teacher</router-link> |
    <router-link to="/manager">manager</router-link>
  </nav> -->
  <router-view/>
</template>

<style lang="less">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  color: #2c3e50;
}
*{
  margin: 0;
  padding: 0;
}
nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
