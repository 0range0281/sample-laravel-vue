<template>
  <div id="app">
    <div id="nav">
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/about">About Us</router-link></li>
        <li><router-link to="/login">Login</router-link></li>
      </ul>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:  black;
}

#nav {
  padding: -50px;
  margin-bottom: 30px;
}

#nav a {
  font-weight: bold;
  color: #fff;
}

#nav a.router-link-exact-active {
  color: white;
  opacity: 1;
}

ul{
  list-style-type: none;
  margin: -8px;
  padding: 0;
  overflow: hidden;
  background-color: #1A1E23;
  display: flex;
  justify-content: space-evenly;
}
li a{
  display: block;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  opacity: .4;
}
li a:hover:not(.active){
  opacity: .7;
}
</style>