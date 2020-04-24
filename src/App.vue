<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/skill">Skill</router-link> |
      <router-link to="/contact">Contact</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style scoped lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: end;
  color: #2c3e50;
  font-size: 20px;
}

#nav {
  padding: 10px;

  a {
    font-weight: bold;
    color: #2c3e50;
    text-decoration: none;

    &.router-link-exact-active {
      color: #FF8C00;
      background: -webkit-linear-gradient(0deg, #40E0D0, #FF8C00, #FF0080);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
  }
  a:hover {
    text-decoration: underline;
  }
}

@media only screen and (max-width: 600px) {
  #nav {
    justify-content: flex-start;
    display: flex;
  }
}
</style>