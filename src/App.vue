<template>
  <div id="app">
    <b-container>
      <b-row class="mb-5">
        <b-col>
              <h2 class="text-success">Tim Zagelow</h2>
        </b-col>
      </b-row>

      <b-row>
        <b-col>
          <h4>Experience</h4>
          <experience></experience>
        </b-col>
      </b-row>

      
      <h4>Skills</h4>
      <skills></skills>
    </b-container>
  </div>
</template>

<script>

import Experience from "./components/Experience";
import Skills from "./components/Skills";

export default {
  name: 'App',
  components: {
    Experience,
    Skills,
  },
  created() {
    document.title = "Tim Zagelow";
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin-top: 30px;
}
</style>
