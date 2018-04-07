<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li>
        <router-link to="/page1">Go to Page 1</router-link>
      </li>
      <li>
        <router-link to="/page2">Go to Page 2</router-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App',
    };
  },
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
</style>
