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

  @media only screen and (max-width: 375px) {
    .main{
      display: block;
    }
    
  }
  
@media only screen and (min-width: 375px) {
  .main{
    display: grid;
    grid-template-columns: 1fr 4fr;
    grid-template-areas: 
        "sidemenu body";
    
  }

  .sidemenu {
    background-color: #c7eff2;
   
  }
  .body {
    background-color: #e6f4f5;
    text-align: center;

  }
}

</style>
