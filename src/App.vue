<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view/>
  </div>
</template>

<style lang="scss">
#app, div#home, div#Home {
  text-align: center;
  height:80%;
  width:auto;
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

h1,h2,h3,h4,h5,h6 {
  font-family:"Permanent Marker", cursive;
}

p, div, span, li {
  font-family:"Averia Libre", cursive;
}
</style>
