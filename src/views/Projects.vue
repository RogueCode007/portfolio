<template>
  <div class="projects">
    
    <p class="text-red-500 text-lg md:ml-6">Explore some of my works</p>
    <div class="project-tiles mt-6 lg:mx-auto">

      <div class="tile">
        <div class="image-div  bg-cover bg-no-repeat" v-bind:style="{ backgroundImage: 'url(' + etranz + ')'}"></div>
        <h3 class="title">etranzact web</h3>
        <div class="stack">
          <span class="vue">Vue</span>
          <span class="css">CSS</span>
          <span class="api">Tailwind</span>
        </div>
        <p class="description text-white">A website project for etranzact built primarily with VueJs, eventually connected to a Laravel backend</p>
        <a target="blank" href="https://www.etranzact.com/#/" class="text-2xl inline"><span class="iconify text-white inline" data-icon="octicon:link-24" data-inline="false"></span></a>
        <a target="blank" href="https://github.com/RogueCode007/etranzact" class="text-2xl inline ml-5"><span class="iconify text-white inline" data-icon="line-md:github" data-inline="false"></span></a>
      </div>

      <div class="tile mt-12">
        <div class="image-div  bg-cover bg-no-repeat" v-bind:style="{ backgroundImage: 'url(' + pd + ')'}"></div>
        <h3 class="title">paddycover</h3>
        <div class="stack">
          <span class="vue">Vue</span>
          <span class="css">CSS</span>
          <span class="api">Tailwind</span>
          <span class="api">API</span>
        </div>
        <p class="description text-white">A fullstack web application for purchasing various types of insurance with the added benefit of paying small small</p>
        <a target="blank" href="https://paddymain.netlify.app" class="text-2xl inline"><span class="iconify text-white inline" data-icon="octicon:link-24" data-inline="false"></span></a>
        <!-- <p class="text-2xl inline ml-5 text-opacity-50"><span class="iconify text-white inline opacity-30" data-icon="line-md:github" data-inline="false"></span></p> -->
      </div>

      <div class="tile mt-12">
        <div class="image-div  bg-cover bg-no-repeat" v-bind:style="{ backgroundImage: 'url(' + leasy + ')'}"></div>
        <h3 class="title">windbnb</h3>
        <div class="stack">
          <span class="s3">Amazon S3</span>
          <span class="vue">Vue</span>
          <span class="css">CSS</span>
          <span class="api">Tailwind</span>
          <span class="laravel">Laravel</span>
          <span class="api">API</span>
          <span class="mysql">Mysql</span>
        </div>
        <p class="description text-white">A fullstack airbnb clone built with laravel and VueJs, hosting property images on Amazon s3</p>
        <a target="blank" href="http://leasyng.herokuapp.com" class="text-2xl inline"><span class="iconify text-white inline" data-icon="octicon:link-24" data-inline="false"></span></a>
        <a target="blank" href="https://github.com/RogueCode007/windbnb" class="text-2xl inline ml-5"><span class="iconify text-white inline" data-icon="line-md:github" data-inline="false"></span></a>
      </div>

      <div class="tile mt-12">
        <div class="image-div bg-cover bg-no-repeat" v-bind:style="{ backgroundImage: 'url(' + xp + ')'}"></div>
        <h3 class="title">xpatag </h3>
        <div class="stack">
          <span class="vue">Vue</span>
          <span class="css">CSS</span>
          <span class="api">API</span>
        </div>
        <p class="description">An agri-tech platform that connects farm and business owners to various experts in the field</p>
        <a target="blank" href="https://xpataghome.herokuapp.com/" class="text-2xl inline"><span class="iconify text-white inline" data-icon="octicon:link-24" data-inline="false"></span></a>
        <!-- <a target="blank" href="https://github.com/RogueCode007/geoquiz" class="text-2xl inline ml-5"><span class="iconify text-white inline" data-icon="line-md:github" data-inline="false"></span></a> -->
      </div>
      <div class="tile mt-12">
        <div class="image-div bg-cover bg-no-repeat" v-bind:style="{ backgroundImage: 'url(' + geoquiz + ')'}"></div>
        <h3 class="title">Country Quiz</h3>
        <div class="stack">
          <span class="vue">Vue</span>
          <span class="css">CSS</span>
          <span class="api">API</span>
        </div>
        <p class="description">A fun quiz about countries, consumes an API to display questions about random countries</p>
        <a target="blank" href="https://roguecode007.github.io/geoquiz" class="text-2xl inline"><span class="iconify text-white inline" data-icon="octicon:link-24" data-inline="false"></span></a>
        <a target="blank" href="https://github.com/RogueCode007/geoquiz" class="text-2xl inline ml-5"><span class="iconify text-white inline" data-icon="line-md:github" data-inline="false"></span></a>
      </div>

      <div class="tile mt-12">
        <div class="image-div bg-cover bg-no-repeat" v-bind:style="{ backgroundImage: 'url(' + weatherapp + ')'}"></div>
        <h3 class="title">Weather App</h3>
        <div class="stack">
          <span class="vue">Vue</span>
          <span class="css">CSS</span>
          <span class="api">API</span>
        </div>
        <p class="description">A weather app that fetches weather information of a user's location or of that of a searched city</p>
        <a target="blank" href="https://roguecode007.github.io/weatherapp" class="text-2xl inline"><span class="iconify text-white inline" data-icon="octicon:link-24" data-inline="false"></span></a>
        <a target="blank" href="https://github.com/RogueCode007/weatherappcode" class="text-2xl inline ml-5"><span class="iconify text-white inline" data-icon="line-md:github" data-inline="false"></span></a>
      </div>

      
      <div class="tile mt-12">
        <div class="image-div bg-cover bg-no-repeat" v-bind:style="{ backgroundImage: 'url(' + shevil + ')'}"></div>
        <h3 class="title">E-commerce App</h3>
        <div class="stack">
          <span class="laravel">Laravel</span>
          <span class="bootstrap">Bootstrap</span>
          <span class="mysql">Mysql</span>
          <span class="css">CSS</span>
          <span class="s3">Amazon S3</span>
        </div>
        <p class="description">A full stack, fashion store-like web application with photo adding features by an admin.</p>
        <a target="blank" href="http://shevil.herokuapp.com" class="text-2xl inline"><span class="iconify text-white inline" data-icon="octicon:link-24" data-inline="false"></span></a>
        <a target="blank" href="https://github.com/RogueCode007/pop" class="text-2xl inline ml-5"><span class="iconify text-white inline" data-icon="line-md:github" data-inline="false"></span></a>
      </div>

      <!-- <div class="tile mt-12">
        <div class="image-div bg-cover bg-no-repeat" v-bind:style="{ backgroundImage: 'url(' + pd + ')'}"></div>
        <h3 class="title">PaddyCover user dashboard</h3>
        <div class="stack">
          <span class="vue">Vue</span>
          <span class="bootstrap">Bootstrap</span>
          <span class="css">CSS</span>
        </div>
        <p class="description">A user dashbaord for an insure-tech company built using Bootstarp's Core UI</p>
        <a target="blank" href="https://infallible-euler-1f2063.netlify.app" class="text-2xl inline"><span class="iconify text-white inline" data-icon="octicon:link-24" data-inline="false"></span></a>
        <a target="blank" href="https://github.com/RogueCode007/paddycover-user" class="text-2xl inline ml-5"><span class="iconify text-white inline" data-icon="line-md:github" data-inline="false"></span></a>
      </div> -->

    </div>
  </div>
</template>
<script>
import shevil from "@/assets/shevilsnapshot.png"
import geoquiz from "@/assets/geoquizsnapshot.png"
import leasy from "@/assets/leasysnapshot.png"
import weatherapp from "@/assets/weatherappsnapshot.png"
import pd from "@/assets/pd.png"
import xp from "@/assets/xp.png"
import etranz from "@/assets/etranz.png"

export default {
  data(){
    return {
      etranz: etranz,
      shevil : shevil,
      geoquiz : geoquiz,
      leasy : leasy,
      weatherapp : weatherapp,
      pd: pd,
      xp: xp
    }
  },

}
</script>
<style lang="scss" scoped>
div.projects{
  margin-top: 60px;
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
.image-div{
  height: 250px;
  border-radius: 24px;
  border: 1px solid  rgb(107, 114, 128);
}
h3{
  color: #000000;
  margin-bottom: 5px;
}
span{
  color: #000000;
  border: none;
  margin-right: 5px;
  font-size: 0.8em
}
.description{
  margin: 5px 0;
  font-size: 0.95em;
}
.title{
  color: #fff;
}
.vue, .nuxt{
  background-color: #41b883;
}
.laravel{
  background-color: #fb503b;
}
.bootstrap{
  background-color: #563d7c;
}
.css{
  background-color: #2965f1;
}
.mysql{
  background-color: #f29111;
}
.api{
  background-color: #00758f;
}
.s3{
  background-color: #ff9900;
}

@media only screen and (min-width: 768px){
  div.tile{
    width: 45%;
    margin: 2.5%;
    display: inline-block;
  }
}
@media screen and (min-width: 1024px){
  div.tile{
    width: 30%;
    margin: 1.667%;
  }
}
</style>