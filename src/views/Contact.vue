<template>
  <div class="contacts">
    <h1>Let's talk</h1>
    <hr>
    <p>If you have a project in mind or are simply interested in my awesome self, get in touch and let's get things moving</p>
    <p class="mt-4 font-bold">May the force be with you!</p>
    <div class="icons">
      <a target="blank" href="https://mobile.twitter.com/Bioye7"><span class="iconify contact" data-icon="ant-design:twitter-outlined" data-inline="false"></span></a>
      <a target="blank" href="https://github.com/RogueCode007"><span class="iconify contact" data-icon="ant-design:github-filled" data-inline="false"></span></a>
      <a target="blank" href="http://linkedin.com/in/feyifoluwa-abioye-1296351bb"><span class="iconify contact" data-icon="bx:bxl-linkedin" data-inline="false"></span></a>
    </div>

  </div>
</template>
<script>

import white from "@/assets/white.jpg"

export default {
  data(){
    return {
      
      white: white
    }
  }
  
}
</script>
<style lang="scss" scoped>

div.contacts{
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
  color: white;
  margin-bottom: 30px
}
hr{
  border-top: 1px solid #797979;
  border-bottom: none;
  width: 25%;
}
p{
  margin-top: 20px; 
  color: #797979;
  font-size: 1em
}
.icons{
  margin-top: 20px;
  display: flex;
  align-items: center;
}
.contact{
  color: #797979;
  font-size: 1.6em;
  margin-right: 15px;
}
@media only screen and (min-width: 650px){
  div.contacts{
    max-width: 700px;
    margin: 100px auto;
  }
  hr{
    width: 15%;
  }
}

</style>