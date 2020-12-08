<template>
    <nav>
      <div>
        <h3 class="logo">Obiwan Pelosi</h3>
        <button v-show="!shownav" @click="toggle" class="toggler"><span  class="iconify bar" data-icon="clarity:bars-line" data-inline="false"></span></button>
        <button v-if="shownav" @click="toggle" class="cross"><span class="iconify cancel" data-icon="topcoat:cancel" data-inline="false"></span></button>
        <ul class="show-desktop">
          <li><router-link to="/">Home</router-link></li>
          <!-- <li><router-link to="#">Resume</router-link></li> -->
          <li><router-link to="/projects">Projects</router-link></li>
          <li><router-link to="/contact">Contact Me</router-link></li>
        </ul>
      </div>
      <ul v-if="shownav" class="show-mobile">
        <li @click="toggle"><router-link to="/" >Home</router-link></li>
        <!-- <li><router-link to="#">Resume</router-link></li> -->
        <li @click="toggle"><router-link to="/projects">Projects</router-link></li>
        <li @click="toggle"><router-link to="/contact">Contact Me</router-link></li>
      </ul>
      
    </nav>
</template>

<script>
export default {
  name: 'NavBar',
  props:{
    shownav: Boolean
  },
  methods:{
    toggle(){
      this.$emit('toggleNav')
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
button{
  border: none;
  background-color: #000000;
  outline: none;
}

nav div{
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 0;
}
.show-desktop{
  display: none;
}
.show-mobile{
  margin-top: 20px;
  list-style-type: none;
  opacity: 1;
  animation-name: fade;
  animation-duration: 2s;
  animation-iteration-count: 1;
  animation-fill-mode: forwards;
  
}
@keyframes fade {
  0%{
    opacity: 0
  }
  100%{
    opacity: 1;
  }
}
.show-mobile li{
  margin: 30px 0;
  
}
.show-mobile li a{
  text-decoration: none;
  color: #fff;
  font-size: 0.9em;
  transition: 0.5s
}
.show-mobile a:hover{
  color: #797979;
}

.cancel{
  font-size: 1.8em;
  font-weight: 200;
  color: #eeeeee;
  cursor: pointer;
  position: relative;
  
  animation-name: fade;
  animation-duration: 2s;
  animation-iteration-count: 1;
  animation-fill-mode: forwards;
}
.bar{
  font-size: 2em;
  color: #eeeeee;
  cursor: pointer;
  animation-name: fade;
  animation-duration: 2s;
  animation-iteration-count: 1;
  animation-fill-mode: forwards;
}
@media only screen and (min-width: 650px){
  ul.show-desktop{
    display: block;
    display: flex;
    list-style-type: none;
  }
  .show-desktop li{
    margin: 0 15px 0 0;
  }
  .show-desktop li a{
    margin-right: 20px;
  }
  .show-desktop a{
    color: #fff;
    text-decoration: none;
    font-size: 0.9em;
    transition: 0.5s;
  }
  .show-desktop a:hover{
    color: #797979;
  }
   
  .toggler{
    display: none;
  }
  .show-mobile{
    display: none;
  }
  .cross{
    display: none
  }
}
</style>
