<template>
  <div class="hello">
    <h1>{{ localmsg }}</h1>
    <input v-model = "localmsg" />

    <!-- <p>
    タイトル<br>
       check out the 
    </p> -->


    

      <!-- <a href="https://www.google.co.jp/search?q=%E3%83%A1%E3%83%83%E3%82%BB%E3%83%BC%E3%82%B8+%E3%82%A6%E3%82%A3%E3%83%B3%E3%83%89%E3%82%A6+%E3%83%9A%E3%83%AB%E3%82%BD%E3%83%8A+5+%E5%90%B9%E3%81%8D%E5%87%BA%E3%81%97+%E7%B4%A0%E6%9D%90&tbm=isch&hl=ja&sa=X&ved=2ahUKEwi955jYwYuCAxUTr1YBHXiQBC0QrNwCKAB6BQgBEIMB&biw=1458&bih=698" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
  </div> -->
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












