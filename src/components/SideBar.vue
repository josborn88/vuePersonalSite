<template>
  <div class="sidebar">
    <h1>This is a side bar</h1>
    <h3>It has menus like things on it.</h3>

    <div class="experince">
      <p>Projects</p>
      <p>description and link to ES</p>
      <p>Java</p>
      <p>Python</p>
    </div>

    <div class="contact-info">
      <p>Social media</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.sidebar {
  border-right-style: solid;
  border-right-width: 1px;
}
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

.contact-info {
  padding-top: 20px;
}
</style>
