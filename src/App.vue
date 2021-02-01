<template>
  <div id="app">
    111
    <div id="cccc" contenteditable="true" style="border:1px solid #eee; width:500px; height:500px">
    </div>
    <div @click="test">看看html'</div>
    <!-- <div id="nav">
      <router-link to="/">Home</router-link>
      |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/> -->
  </div>
</template>
<script>
export default {
  methods: {
    test() {
      console.log(11111)
      console.log(document.getElementById("cccc").innerHTML)
    }
  }
}
</script>
<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding-bottom: 20px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
