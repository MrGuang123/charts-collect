<!--
 * @Description:
 * @Autor: yantingguang@tusdao.com
 * @Date: 2020-01-20 15:01:34
 * @LastEditors: yantingguang@tusdao.com
 * @LastEditTime: 2020-01-20 15:21:53
 -->
<template>
  <div id="app">
    <header class="header"></header>
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.header {
  height: 80px;
  background: pink;
}

#nav {
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
