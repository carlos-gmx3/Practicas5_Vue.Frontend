<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
:root {
  --rojoKittsu: #861811;
  --moradoKittsu: #583d8f;
  --azulKittsu: #262859;
}
@font-face {
  font-family: 'Japan';
  src: url('../public/fonts/Japan.ttf');
}
@import url('https://fonts.googleapis.com/css2?family=Ubuntu+Condensed&display=swap');
html {
  box-sizing: border-box;
}
*, *:before, *:after {
  box-sizing: inherit;
}
* {
  margin: 0;
  padding: 0;
}
.container {
  margin: 0 auto;
  max-width: 1100px;
  width: 90%;
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
