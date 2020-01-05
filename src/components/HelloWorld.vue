<template>
  <div class="hello">
    <h1>Welcome!</h1>
    <p>I am a software developer and life long learner.</p>
    <p>Before becoming a developer I worked for about a decade at a science museum creating and presenting
      interactive demonstrations about a wide range of topics, programming a digital planetarium system, 
      and presenting shows for hundreds of people</p>
    
    <p>After learning some basic programming and creating a few tools to automate some of the more boring
      aspects of my job a new passion ignited in me. The ability to create tools to ease our lives, being
      able to take a blank page and create a real product was deeply satisfying and I had to have more of that
      feeling!</p>

    <p>After a bit of reflection I decided it was time for a change. I quit my job at the museum and signed up
      for a programming boot camp though Tech Elevator, I choose to devote myself full time to learning software
      development.</p>
    

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
