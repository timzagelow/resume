<template>
  <div id="app">
    <b-container>
      <b-row class="mb-5">
        <b-col>
              <h2 class="text-success">Tim Zagelow</h2>
        </b-col>
      </b-row>

      <b-row class="mb-5">
        <b-col cols="6">
          <h4>About Me</h4>
          <h5><em>I am passionate about solving challenging technology problems. I hold myself to the highest standard with regards to engineering, teamwork and aesthetics.</em></h5>
          <h5 class="mt-3"><em>My interests include blockchain/web3, crypto, freedom, weight-lifting and vinyl records.</em></h5>
        </b-col>

        <b-col>
          <h4>Contact</h4>
          <b-list-group>
            <b-list-group-item>Phone: 503-758-8384</b-list-group-item>
            <b-list-group-item>Email: <b-link href="mailto:timzagelow@gmail.com">timzagelow@gmail.com</b-link></b-list-group-item>
            <b-list-group-item>Code: <b-link href="https://github.com/timzagelow">GitHub</b-link></b-list-group-item>

          </b-list-group>
        </b-col>
      </b-row>

      <b-row class="mb-5">
        <b-col>
          <h4>Experience</h4>
          <experience></experience>
        </b-col>
      </b-row>

      <h4>Skills</h4>
      <skills></skills>

      <b-row class="mt-5 mb-3">
        <b-col class="text-center">
          <h5 class="text-secondary"><em>Built with Vue &amp; Bootstrap; deployed on <b-link target="_blank" href="https://fleek.co/">Fleek</b-link>/<b-link target="_blank" href="https://dfinity.org/">Internet Computer</b-link></em></h5>
        </b-col>
      </b-row>
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
