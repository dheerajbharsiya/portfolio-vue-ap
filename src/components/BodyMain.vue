<template>
  <div class="section-intro" id="intro">
    <div class="background-grad">
      <div class="row align-items-center">
        <div class="col-xl-3 col-lg-5 col-md-5 col-sm-4 p50-top">
          <div class="db_image float-right">
            <img src="./../assets/circle-cropped.png" alt="dheeraj" />
          </div>
        </div>
        <div class="col-xl-4 col-lg-7 col-md-7 col-sm-8">
          <div class="my_intro float-left">
            <h1>
              Hi There! I am Dheeraj <br />
              Web Devlopment Engineer
            </h1>
            <p><i> Current : Senior Software Engineer at Factset</i></p>
          </div>
        </div>
        <div class="col-sm-4">
          <div class="card">
            <div class="card-body">
              <h2 class="card-title">My Blogs</h2>
              <a class="card-link" href="https://dheerajbharsiya.medium.com/proxy-objects-in-javascript-javascript-es6-7b07e88b1cd1"><p class="card-text">Proxy Objects In Javascript ES6</p></a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="section-expertise container">
      <div class="section-expertise-heading">
        <h2 class="text-gray">Area of Expertise</h2>
      </div>
      <div class="row" id="skills">
        <div class="col-lg-4">
          <a href="#" class="box-skills d-flex p-4 rounded mb-4">
            <div class="mr-3">
              <img
                src="./../assets/web_apps_icon.png"
                class="icon icon_javascript"
              />
            </div>
            <div class="skill-text">
              <h3 class="skill-h3">Web Application Architecture</h3>
              <p>I can help with Desiging and Developing the Architecture of modern Web Apps.</p>
            </div>
          </a>
        </div>
        <div class="col-lg-4">
          <a href="#" class="box-skills d-flex p-4 rounded mb-4">
            <div class="mr-3">
              <img
                src="./../assets/javascript_icon.png"
                class="icon icon_javascript"
              />
            </div>
            <div class="skill-text">
              <h3 class="skill-h3">Javascript</h3>
              <p>I like to deep dive into the granularities of Javascript.</p>
            </div>
          </a>
        </div>
        <div class="col-lg-4">
          <a href="#" class="box-skills d-flex p-4 rounded mb-4">
            <div class="mr-3">
              <img
                src="./../assets/nodejs-icon.svg"
                class="icon icon_javascript"
              />
            </div>
            <div class="skill-text">
              <h3 class="skill-h3">NodeJS</h3>
              <p>Have worked on projects with NodeJs, Graphql and OracleDB</p>
            </div>
          </a>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-4">
          <a href="#" class="box-skills d-flex p-4 rounded mb-4">
            <div class="mr-3">
              <img
                src="./../assets/frameworks_icon.png"
                class="icon icon_javascript"
              />
            </div>
            <div class="skill-text">
              <h3 class="skill-h3">Frameworks (Angular, VueJs)</h3>
              <p>Currently working on VueJs and have executed many Angular Projects</p>
            </div>
          </a>
        </div>
        <div class="col-lg-4">
          <a href="#" class="box-skills d-flex p-4 rounded mb-4">
            <div class="mr-3">
              <img
                src="./../assets/sql_icon.png"
                class="icon icon_javascript"
              />
            </div>
            <div class="skill-text">
              <h3 class="skill-h3">SQL (Oracle/MSSQL)</h3>
              <p>Have worked on simple sql queries to creating complex stored procedures.</p>
            </div>
          </a>
        </div>
        <div class="col-lg-4">
          <a href="#" class="box-skills d-flex p-4 rounded mb-4">
            <div class="mr-3">
              <img
                src="./../assets/typescript_icon.png"
                class="icon icon_javascript"
              />
            </div>
            <div class="skill-text">
              <h3 class="skill-h3">TypeScript</h3>
              <p>Good At TypeScript.</p>
            </div>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({})
export default class BodyMain extends Vue {}
</script>

<style>
.card {
  box-shadow: 2px 0px 0px 6px #f0f0f0;
}

a.card-link {
  text-decoration-line: none;
  text-align: left;
}

a p.card-text {
  color : #22BECA;
  font-size: 26px;
  font-style: italic;
  font-family: cursive;
  text-decoration-style: none;
}

.card-title {
  text-align: left;
  font-weight: bold;
  color: gray;
}

.db_image img {
  width: 250px;
  height: 250px;
}

.background-grad {
  background: url("./../assets/orange_grad.png");
  background-repeat: no-repeat;
  background-size: cover;
  height: 400px;
}

.my_intro {
  color: aliceblue;
}

.p50-top {
  padding-top: 50px;
}

.float-left {
  float: left;
}
.float-right {
  float: right;
}

.box-skills {
  /* background: rgba(0, 0, 0, 0.5); */
  /* background: rgb(7 0 0 / 94%); */
  text-decoration-line: none !important;
}

.icon {
  width: 60px;
  height: 60px;
}

.text-gray {
  font-weight: bold;
  font-size: 30px;
  margin-top: 20px;
}

.skill-h3 {
  color: hsl(184deg 100% 34%);
  text-decoration: none;
  font-style: italic;
  font-family: cursive;
}

.rounded {
  border-radius: 0.25rem !important;
}

.skill-text {
  margin-left: 10px;
  min-width: 100px;
}
.skill-text p {
  font-size: 12px;
  color: #979494;
}
</style>
