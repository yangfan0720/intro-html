<template>
  <div id="app">
    <div id="nav">
	  <ul>
		  <router-link tag="li" to="/home">首页</router-link>
		  <router-link tag="li" to="/clothes">服装</router-link>
		  <router-link tag="li" to="/shoe">鞋子</router-link>
		  <router-link tag="li" to="/decorations">饰品</router-link>
		  <router-link tag="li" to="/daily">日化</router-link>
		  <router-link tag="li" to="/about">关于我们</router-link>
	  </ul>
    </div>
    <router-view/>
  </div>
</template>

<style>
	*{
		margin: 0;
		padding: 0;
	}
	body{
		background-color: #f9f9f9;
	}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  width: 100%;
  height: 60px;
  background-color: #F92424;
  line-height: 60px;
}

#nav li{
  font-weight: bold;
  color: #838383;
  display: inline-block;
  padding: 0 50px;
  cursor: pointer;
}

#nav li.router-link-exact-active {
  color: #FFFFFF;
}
</style>
