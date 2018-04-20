<template>
  <div id="app">
    <div>
      <router-link to="/">首页</router-link> |
      <router-link :to="{name:'hi',params:{username:'pop',id:'000'}}">hi</router-link> |
      <router-link to="/hi1">hi1</router-link> |
      <router-link to="/hi2">hi2</router-link> |
    </div>
    <!--<p>{{$route.name}}</p>-->
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
