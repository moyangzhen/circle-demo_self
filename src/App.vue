<template>
  <div id="app">
    <nav>
      <router-link class="link-item" to="/">HTML</router-link>
      <router-link class="link-item" to="/about">CSS</router-link>
      <router-link class="link-item" to="/about">JavaScript</router-link>
      <router-link class="link-item" to="/about">Vue</router-link>
      <router-link class="link-item" to="/about">设计模式</router-link>
    </nav>
    <router-view />
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  display: flex;
  justify-content: space-between;
  .link-item {
    flex: 1;
  }
}
</style>
