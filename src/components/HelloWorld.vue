<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>黄金帅</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">黄金帅在次</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">谁敢造次</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">我</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">是</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">黄</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">金</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">帅</a></li>
    </ul>
    <h1>黄金帅</h1>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">帅</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">帅</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">帅</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">帅</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">帅</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
