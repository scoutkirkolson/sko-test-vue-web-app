<template>
  <div class="hello">
    <current-time time-zone="Singapore"><span slot="prefix">Singapore time: </span></current-time>
  </div>
</template>

<script>
//import Components from '@scoutkirkolson/sko-test-vue-npm-library'
//import '@scoutkirkolson/sko-test-vue-npm-library/dist/sko-test-vue-npm-library.css'
import Vue from 'vue';
import CurrentTime from '@scoutkirkolson/vite-current-time-component'

export default {
  name: 'HelloWorld',
  components: {
    CurrentTime,
  },
  props: {
    msg: String
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
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
