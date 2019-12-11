<template>
  <div class="hello">
    <h1>Hello Docker!</h1>
    <p>This is a small example of how you can use Docker, Docker Hub, Github Actions and Watchtower</p>
    <h4>v0.1</h4>
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
