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
    </b-container>
  </div>
</template>

<script>

import Experience from "./components/Experience";
// import Experience from './components/Experience.vue';

export default {
  name: 'App',
  components: {
    Experience
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
