<template>
  <div id="app">
    <Navbar/>
    <div id="main">
      <router-view/>
    </div>
  </div>
</template>
<script>
import Navbar from "@/components/Navbar.vue";

export default {
  components: {
    Navbar
  }
}
</script>
<script src="./assets/js/main.js"></script>
