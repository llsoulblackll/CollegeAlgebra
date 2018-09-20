<template>
  <div id="app">
    <Navbar/>
    <div id="main">
      <router-view @click.native="hideNav()"/>
    </div>
  </div>
</template>
<script>
import Navbar from "@/components/Navbar.vue";

export default {
  components: {
    Navbar
  },
  methods: {
    hideNav() {
      //CSS ANIM LASTS 1s
      if($('#header').hasClass('showNav'))
        $('#header').removeClass('showNav').addClass('hideNav');
    }
  }
}
</script>
<!--<script src="./assets/js/main.js"></script>-->
