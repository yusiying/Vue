<template>
  <div>
    <h1>{{ $route.params.username}}-{{$route.params.id}}</h1>
    <h3>{{message}}</h3>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
 name: "hi",
 data(){
 return {
  message:"测试页面"
 }
 }
 }
</script>

<style scoped>

</style>
