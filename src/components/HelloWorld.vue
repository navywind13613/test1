<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>hello</h2>
    <div class="amap-wrapper">
      <el-amap class="amap-box" :vid="'amap-vue'"></el-amap>
    </div>
    <div id="container"></div>
  </div>
</template>

<script>
import { Button, message } from "ant-design-vue";

export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
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
.amap-wrapper {
  width: 500px;
  height: 500px;
}
</style>
