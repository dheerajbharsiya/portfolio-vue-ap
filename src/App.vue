<template>
  <div>
    <Header></Header>
    <BodyMain></BodyMain>
    <div class="db-footer" id="contact">
      <div
        class="row contact-info"
        style="
          margin-top: 25px;
          color: white;
          font-weight: bold;
          font-size: 20px;
        "
      >
        <div class="col-xl-4">
          <a href="https://www.linkedin.com/in/dheerajbharsiya/"
            ><img class="icon" src="./assets/linkedin_icon.gif" />
            LinkedIn</a
          >
        </div>
        <div class="col-xl-4">
          <a href="https://www.facebook.com/dheerajfact"
            ><img class="icon" src="./assets/facebook_icon.gif" />
            Facebook</a
          >
        </div>
        <div class="col-xl-4">
          <a href="https://github.com/dheerajbharsiya"><img class="icon" src="./assets/github_icon.png" /> Github</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/Header.vue";
import BodyMain from "./components/BodyMain.vue";

@Options({
  components: {
    HelloWorld,
    Header,
    BodyMain,
  },
})
export default class App extends Vue {}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.db-footer {
  background: #5d5e5f;
}

.db-footer {
  position: absolute;
  height: 140px;
  width: 100%;
}

.db-footer a {
  color : white;
}

.body-main {
  background-repeat: no-repeat;
  background: url("./assets/orange_grad.png");
}
</style>
