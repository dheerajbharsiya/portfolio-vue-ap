<template>
  <div>
    <div class="db-header">
      <div class="row" style="padding-top: 6px">
        <div class="db-header-ribbon"></div>
        <div class="db-header-ribbon db-header-ribbon-short"></div>
        <div class="db-header-ribbon db-header-ribbon-shortest"></div>
      </div>
      <div class="container-fluid">
        <div class="row">
          <div class="col-lg-4 db-header-left m2-top text-mixed">
            <h1 class="text-uppercase text-white">Dheeraj Bharsiya</h1>
            <p class="mb-0 db-desc text-skyish">
              Motivated, Goal Driven Software Engineer
            </p>
          </div>
          <div class="col-lg-8 db-header-right float-sm-right">
            <nav class="navbar navbar-expand-lg">
              <div class="collapse navbar-collapse tm-nav" id="navbarNav">
                <!-- Links -->
                <ul class="navbar-nav margin-left-auto text-white">
                  <li class="nav-item active">
                    <a class="nav-link tm-nav-link" href="#intro"
                      >Home <span class="sr-only"></span
                    ></a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link tm-nav-link" href="#skills">Skills</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link tm-nav-link" href="#contact">Contact</a>
                  </li>
                  <li class="nav-item">
                    <a
                      class="nav-link tm-nav-link"
                      href="mailto:dheerajbharsiya@gmail.com">
                      <img class="icon" src="./../assets/mail_icon.png" />
                    </a>
                  </li>
                </ul>
              </div>
            </nav>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
@Options({
  props: {
    msg: String,
  },
})
export default class Header extends Vue {
  msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.db-header,
.db-footer {
  background: #5d5e5f;
}

.db-footer {
  position: fixed;
  bottom: 0;
  height: 140px;
  width: 100%;
}

/* .db-body {
    background: #969da5;
} */

.db-header-ribbon {
  width: 100%;
  margin-left: auto;
  background: #22beca;
  height: 7px;
}
.db-header-ribbon-short {
  width: 90%;
  margin-left: auto;
  background: #f7a873;
  height: 7px;
  margin-top: 7px;
}
.db-header-ribbon-shortest {
  width: 80%;
  margin-left: auto;
  background: white;
  height: 5px;
  margin-top: 7px;
}

.m4-top {
  margin-top: 20px;
}

.text-white {
  color: white;
}
.text-mixed {
  color: #969da5;
}

.text-skyish {
  color: #22beca;
  font-weight: bold;
  font-style: italic;
  font-family: cursive;
  font-size: 16px;
}

.text-white li a {
  color: white;
  font-size: 20px;
  font-weight: bold;
}
.margin-left-auto {
  margin-left: auto;
}
</style>
