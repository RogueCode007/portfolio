<template>
  <div class="container">
    <div class="main">
      <h1>I'm Obiwan-pelosi and I love to build beautiful and functional websites</h1>
      <hr>
      <p>I currently use frameworks like Vue, Laravel and jQuery. Check out some of my <router-link to="/projects">projects</router-link></p>
      <div class="icons">
        <a target="blank" href="https://mobile.twitter.com/Bioye7"><span class="iconify contact" data-icon="ant-design:twitter-outlined" data-inline="false"></span></a>
        <a target="blank" href="https://github.com/RogueCode007"><span class="iconify contact" data-icon="ant-design:github-filled" data-inline="false"></span></a>
        <a target="blank" href="http://linkedin.com/in/feyifoluwa-abioye-1296351bb"><span class="iconify contact" data-icon="bx:bxl-linkedin" data-inline="false"></span></a>
      </div>
    </div>
    <div class="image">
      <img 
      :src="starwars">
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import starwars from "@/assets/star-wars.jpg"

export default {
  name: 'Home',
  data(){
    return {
      starwars: starwars
    }
  }
}
</script>
<style lang="scss" scoped>
.container{
  margin: 60px auto;
  animation-name: fade;
  animation-duration: 2s;
  animation-iteration-count: 1;
  animation-fill-mode: forwards;
  animation-delay: 0s;
}
@keyframes fade {
  0%{
    opacity: 0
  }
  100%{
    opacity: 1;
  }
}

h1{
  font-size: 1.5em;
  line-height: 1.6em;
  margin-bottom: 10px
}

hr{
  border-top: 1px solid #797979;
  border-bottom: none;
  width: 30%;
}

.main p{
  color: #797979;
  font-size: 1em;
  margin: 15px 0
}
p a{
  color: white
}
.icons{
  display: flex;
  align-items: center;
}
.contact{
  color: #797979;
  font-size: 1.6em;
  margin-right: 15px;
}
div.image{
  margin-top: 20px;
}
.image img{
  width: 300px;
  
}
@media only screen and (min-width: 500px){
  h1{
    font-size: 1.8em;
  }
}
@media only screen and (min-width: 950px){
  div.container{
    max-width: 80%;
    display: flex;
  }
  div.main{
    padding-top: 100px;
    padding-right: 10px;
  }
}

@media only screen and (min-width: 1200px){
  .image img{
    width: 400px
  }
}

</style>