<template>
  <div class="hello">
    <h1>スクラッチ　「素数発生機」</h1>
    <h2>by @montowakami</h2>
    <p>
      <iframe
        src="https://scratch.mit.edu/projects/578509784/embed"
        allowtransparency="true"
        width="485"
        height="402"
        frameborder="0"
        scrolling="no"
        allowfullscreen
      ></iframe>
    </p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
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
