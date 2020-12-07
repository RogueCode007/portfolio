<template>
  <div id="app">
    <NavBar v-bind:shownav="shownav" @toggleNav="toggleNavbar"></NavBar>
    <router-view v-show='!shownav'></router-view>
  </div>
</template>
<script>
import NavBar from '@/components/NavBar.vue';
export default {
  components:{
    NavBar,
  },
  data(){
    return{
      shownav : false,
    }
  },
  methods:{
    toggleNavbar(){
      this.shownav = !this.shownav;
    }
  }
}
</script>


<style  lang="scss">
*{
  margin: 0;
  padding: 0;
  
}

body{
  font-family: 'Nunito Sans', sans-serif;
  color: white;
  background-color: #000000;
  padding: 0 15px;
}


</style>
