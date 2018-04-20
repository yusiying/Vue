<template>
  <div class="Params">
    <p>
      {{msg}}
    </p>
    <p>
      newsId:{{$route.params.newsId}}
      newstitle:{{$route.params.newsTitle}}
    </p>
  </div>
</template>

<script>
export default {
  name: 'Params',
  data () {
    return {
      msg: 'Params msg'
    }
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
