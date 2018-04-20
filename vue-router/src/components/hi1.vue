<template>
  <div>
    <h2>{{message}}</h2>
    <router-view></router-view>
  </div>
</template>

<script>
 export default {
  name: "hi1",
   data(){
    return {
      message:"测试页面1"
    }
   }
 }
</script>

<style scoped>

</style>
