<template>
  <div>
    <h2>{{message}}</h2>
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
