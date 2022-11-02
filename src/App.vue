<template>
  <div id="app">
    <b-container>
      <b-row class="mb-5">
        <b-col>
              <h2 class="text-success">voidmanevoid</h2>
        </b-col>
      </b-row>

      <b-row>
        <b-col sm="6" class="mb-5">
          <h4>About Me</h4>
          <h5><em>I am passionate about solving challenging technology problems. I hold myself to the highest standard with regards to engineering, teamwork and aesthetics.</em></h5>
          <h5 class="mt-3"><em>My interests include web3, NFTs, freedom, weight-lifting and vinyl records.</em></h5>

          <h5 class="mt-3"><em>Slowly building a music NFT marketplace with generative audio capabilities. Using React, Python and Metaplex.</em></h5>
        </b-col>

        <b-col class="mb-5">
          <h4>Contact</h4>
          <b-list-group>
            <!-- <b-list-group-item>Phone: 503-758-8384</b-list-group-item> -->
            <b-list-group-item>Email: <b-link href="mailto:voidarelli@protonmail.com">voidarelli@protonmail.com</b-link></b-list-group-item>
            <!-- <b-list-group-item>Code: <b-link href="https://github.com/timzagelow" target="_blank">GitHub</b-link></b-list-group-item> -->
          </b-list-group>

          <h4 class="mt-5">Projects</h4>
          <b-list-group>
            <b-list-group-item><b-link target="_blank" href="https://recordsbymail.com/">Records By Mail</b-link></b-list-group-item>
            <b-list-group-item><b-link target="_blank"  href="https://bassmoney.io/">Bass Money NFT</b-link></b-list-group-item>
            <b-list-group-item><b-link target="_blank"  href="https://twitter.com/cets_sales">Cets Sales Bot</b-link></b-list-group-item>
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
    document.title = "voidmanevoid";
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
