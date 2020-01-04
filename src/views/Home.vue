<template>
  <div class="main">
    <div class="sidemenu">
      <SideBar></SideBar>
    </div>
    
    <div class="body">
      <HelloWorld msg="Welcome to Your Vue.js App"/>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import SideBar from '@/components/SideBar.vue'

export default {
  name: 'home',
  components: {
    HelloWorld,
    SideBar
  }
}
</script>

<style>
  .main{
    display: grid;
     grid-template-columns: 1fr 2fr 2fr;
    grid-template-areas: 
        "sidemenu   body";
  }

  .sidemenu {
    background-color: red;
  }
  .body {
    background-color: blue;
    text-align: center;

  }

</style>
