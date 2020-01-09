<template>
  <div class="main">
    <div class="sidemenu">
      <SideBar></SideBar>
    </div>

    <div class="body">
      <h1>This is where the projects overview goes.</h1>

      <p>I think there will be a highlights and then links to language specific things.</p>
    </div>
  </div>
</template>

<script>
import SideBar from "@/components/SideBar.vue";

export default {
  name: "projects",
  components: {
    SideBar
  }
};
</script>

<style>
.main {
  display: grid;
  grid-template-columns: 1fr 4fr;
  grid-template-areas: "sidemenu body";
}

.sidemenu {
  background-color: #c7eff2;
}
.body {
  background-color: #e6f4f5;
  text-align: center;
}
</style>