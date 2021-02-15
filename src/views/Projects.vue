<template>
  <div class="projects">
    
    <div class="project-tiles">
      <p>These are some projects i've worked on</p>
      <div class="tile">
        <h3 class="title">E-commerce App</h3>
        <div class="stack">
          <span class="laravel">Laravel</span>
          <span class="bootstrap">Bootstrap</span>
          <span class="mysql">Mysql</span>
          <span class="css">CSS</span>
          <span class="s3">Amazon S3</span>
        </div>
        <p class="description">An e-commerce web application for a business owner and consumers. A business owner with admin access can log in and add products (with pictures) to the store while consumers can shop for items.</p>
        <a target="blank" href="http://shevil.herokuapp.com"><span class="iconify" data-icon="octicon:link-24" data-inline="false"></span></a>
      </div>
      <div class="tile">
        <h3 class="title">Country Quiz</h3>
        <div class="stack">
          <span class="vue">Vue</span>
          <span class="css">CSS</span>
          <span class="api">API</span>
        </div>
        <p class="description">A fun quiz about countries, consumes an API to display questions about random countries while keeping count of scores</p>
        <a target="blank" href="https://roguecode007.github.io/geoquiz"><span class="iconify link" data-icon="octicon:link-24" data-inline="false"></span></a>
      </div>
      <div class="tile">
        <h3 class="title">Weather App</h3>
        <div class="stack">
          <span class="vue">Vue</span>
          <span class="css">CSS</span>
          <span class="api">API</span>
        </div>
        <p class="description">A weather app that uses geolocation and consumes the open weather API to display weather information of a user's location or of a searched city</p>
        <a target="blank" href="https://roguecode007.github.io/weatherapp"><span class="iconify link" data-icon="octicon:link-24" data-inline="false"></span></a>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  
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
div.project-tiles{
  max-width: 670px;
  margin: 20px auto
}
div.tile{
  padding: 10px;
  margin: 10px 0;
  background-color: #ffffff;
  border-radius: 5px;
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
  color: #797979;
  font-size: 0.95em;
}
.vue{
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
.link{
  color: #797979
}

</style>